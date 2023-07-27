LoLA Client
###########

To run the client that connects to LoLA, run:

.. code-block:: console

    ros2 run nao_lola_client nao_lola_client


To see all the topics being published and subscribed, in a new terminal, run

.. code-block:: console

    ros2 topic list -t

Topics
******

Below is a list of topics getting published, and topics that this node is subscribed to.

They can be listed while the nao_lola node is running, with:

.. code-block:: console

    ros2 topic list -t

Publishing Topics
*****************

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

Subscription Topics
*******************

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
