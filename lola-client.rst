LoLA Client
###########

To run the client that connects to LoLA, run:

.. code-block:: console

    ros2 run nao_lola_client nao_lola_client

Published Topics
****************

* `sensors/accelerometer` (:ref:`nao_lola_sensor_msgs::msg::Accelerometer <Accelerometer>`)
* `sensors/angle` (:ref:`nao_lola_sensor_msgs::msg::Angle <Angle>`)
* `sensors/buttons` (:ref:`nao_lola_sensor_msgs::msg::Buttons <Buttons>`)
* `sensors/fsr` (:ref:`nao_lola_sensor_msgs::msg::FSR <FSR>`)
* `sensors/gyroscope` (:ref:`nao_lola_sensor_msgs::msg::Gyroscope <Gyroscope>`)
* `sensors/joint_positions` (:ref:`nao_lola_sensor_msgs::msg::JointPositions <sensor_joint_positions>`)
* `sensors/joint_stiffnesses` (:ref:`nao_lola_sensor_msgs::msg::JointStiffnesses <sensor_joint_stiffnesses>`)
* `sensors/joint_temperatures` (:ref:`nao_lola_sensor_msgs::msg::JointTemperatures <JointTemperatures>`)
* `sensors/joint_currents` (:ref:`nao_lola_sensor_msgs::msg::JointCurrents <JointCurrents>`)
* `sensors/joint_statuses` (:ref:`nao_lola_sensor_msgs::msg::JointStatuses <JointStatuses>`)
* `sensors/sonar` (:ref:`nao_lola_sensor_msgs::msg::Sonar <Sonar>`)
* `sensors/touch` (:ref:`nao_lola_sensor_msgs::msg::Touch <Touch>`)
* `sensors/battery` (:ref:`nao_lola_sensor_msgs::msg::Battery <Battery>`)
* `sensors/robot_config` (:ref:`nao_lola_sensor_msgs::msg::RobotConfig <RobotConfig>`)

The following topics are available depending on parameters:

* `imu` (`sensor_msgs::msg::Imu`_) - if :ref:`publish_imu <publish_imu>` parameter is set to true
* `joint_states` (`sensor_msgs::msg::JointState`_) - if :ref:`publish_joint_states <publish_joint_states>` parameter is set to true

Subscribed Topics
*****************

* `effectors/joint_positions` (:ref:`nao_lola_command_msgs::msg::JointPositions <command_joint_positions>`)
* `effectors/joint_stiffnesses` (:ref:`nao_lola_command_msgs::msg::JointStiffnesses <command_joint_stiffnesses>`)
* `effectors/chest_led` (:ref:`nao_lola_command_msgs::msg::ChestLed <ChestLed>`)
* `effectors/left_ear_leds` (:ref:`nao_lola_command_msgs::msg::LeftEarLeds <LeftEarLeds>`)
* `effectors/right_ear_leds` (:ref:`nao_lola_command_msgs::msg::RightEarLeds <RightEarLeds>`)
* `effectors/left_eye_leds` (:ref:`nao_lola_command_msgs::msg::LeftEyeLeds <sensor_LeftEyeLeds>`)
* `effectors/right_eye_leds` (:ref:`nao_lola_command_msgs::msg::RightEyeLeds <sensor_RightEyeLeds>`)
* `effectors/left_foot_led` (:ref:`nao_lola_command_msgs::msg::LeftFootLed <sensor_LeftFootLed>`)
* `effectors/right_foot_led` (:ref:`nao_lola_command_msgs::msg::RightFootLed <sensor_RightFootLed>`)
* `effectors/head_leds` (:ref:`nao_lola_command_msgs::msg::HeadLeds <sensor_HeadLeds>`)
* `effectors/sonar_usage` (:ref:`nao_lola_command_msgs::msg::SonarUsage <SonarUsage>`)

Parameters
**********

.. _publish_imu:

* `publish_imu` (bool, default: `true`)

    Whether to convert `nao_lola sensor_msgs/Accelerometer` and `nao_lola sensor_msgs/Gyroscope` to `sensor_msgs/Imu` and publish it.

.. _publish_joint_states:

* `publish_joint_states` (bool, default: `true`)

    Whether to convert `nao_lola sensor_msgs/JointPositions` to `sensor_msgs/JointState` and publish it.

.. _sensor_msgs::msg::Imu: https://github.com/ros2/common_interfaces/blob/rolling/sensor_msgs/msg/Imu.msg
.. _sensor_msgs::msg::JointState: https://github.com/ros2/common_interfaces/blob/rolling/sensor_msgs/msg/JointState.msg
