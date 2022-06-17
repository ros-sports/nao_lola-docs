Topics
######

Below is a list of topics getting published, and topics that this node is subscribed to.

They can be listed while the nao_lola node is running, with:

.. code-block:: console

    ros2 topic list -t

Publishing Topics
*****************

* `sensors/accelerometer` (`nao_sensor_msgs::msg::Accelerometer`_)
* `sensors/angle` (`nao_sensor_msgs::msg::Angle`_)
* `sensors/buttons` (`nao_sensor_msgs::msg::Buttons`_)
* `sensors/fsr` (`nao_sensor_msgs::msg::FSR`_)
* `sensors/gyroscope` (`nao_sensor_msgs::msg::Gyroscope`_)
* `sensors/joint_positions` (`nao_sensor_msgs::msg::JointPositions`_)
* `sensors/joint_stiffnesses` (`nao_sensor_msgs::msg::JointStiffnesses`_)
* `sensors/joint_temperatures` (`nao_sensor_msgs::msg::JointTemperatures`_)
* `sensors/joint_currents` (`nao_sensor_msgs::msg::JointCurrents`_)
* `sensors/joint_statuses` (`nao_sensor_msgs::msg::JointStatuses`_)
* `sensors/sonar` (`nao_sensor_msgs::msg::Sonar`_)
* `sensors/touch` (`nao_sensor_msgs::msg::Touch`_)
* `sensors/battery` (`nao_sensor_msgs::msg::Battery`_)
* `sensors/robot_config` (`nao_sensor_msgs::msg::RobotConfig`_)

Subscription Topics
*******************

* `effectors/joint_positions` (`nao_command_msgs::msg::JointPositions`_)
* `effectors/joint_stiffnesses` (`nao_command_msgs::msg::JointStiffnesses`_)
* `effectors/chest_led` (`nao_command_msgs::msg::ChestLed`_)
* `effectors/left_ear_leds` (`nao_command_msgs::msg::LeftEarLeds`_)
* `effectors/right_ear_leds` (`nao_command_msgs::msg::RightEarLeds`_)
* `effectors/left_eye_leds` (`nao_command_msgs::msg::LeftEyeLeds`_)
* `effectors/right_eye_leds` (`nao_command_msgs::msg::RightEyeLeds`_)
* `effectors/left_foot_led` (`nao_command_msgs::msg::LeftFootLed`_)
* `effectors/right_foot_led` (`nao_command_msgs::msg::RightFootLed`_)
* `effectors/head_leds` (`nao_command_msgs::msg::HeadLeds`_)
* `effectors/sonar_usage` (`nao_command_msgs::msg::SonarUsage`_)

.. _nao_sensor_msgs::msg::Accelerometer: https://nao-interfaces-docs.readthedocs.io/en/latest/sensor-msgs.html#accelerometer
.. _nao_sensor_msgs::msg::Angle: https://nao-interfaces-docs.readthedocs.io/en/latest/sensor-msgs.html#angle
.. _nao_sensor_msgs::msg::Battery: https://nao-interfaces-docs.readthedocs.io/en/latest/sensor-msgs.html#battery
.. _nao_sensor_msgs::msg::Buttons: https://nao-interfaces-docs.readthedocs.io/en/latest/sensor-msgs.html#buttons
.. _nao_sensor_msgs::msg::FSR: https://nao-interfaces-docs.readthedocs.io/en/latest/sensor-msgs.html#fsr
.. _nao_sensor_msgs::msg::Gyroscope: https://nao-interfaces-docs.readthedocs.io/en/latest/sensor-msgs.html#gyroscope
.. _nao_sensor_msgs::msg::JointCurrents: https://nao-interfaces-docs.readthedocs.io/en/latest/sensor-msgs.html#jointcurrents
.. _nao_sensor_msgs::msg::JointPositions: https://nao-interfaces-docs.readthedocs.io/en/latest/sensor-msgs.html#jointpositions
.. _nao_sensor_msgs::msg::JointStatuses: https://nao-interfaces-docs.readthedocs.io/en/latest/sensor-msgs.html#jointstatuses
.. _nao_sensor_msgs::msg::JointStiffnesses: https://nao-interfaces-docs.readthedocs.io/en/latest/sensor-msgs.html#jointstiffnesses
.. _nao_sensor_msgs::msg::JointTemperatures: https://nao-interfaces-docs.readthedocs.io/en/latest/sensor-msgs.html#jointtemperatures
.. _nao_sensor_msgs::msg::RobotConfig: https://nao-interfaces-docs.readthedocs.io/en/latest/sensor-msgs.html#robotconfig
.. _nao_sensor_msgs::msg::Sonar: https://nao-interfaces-docs.readthedocs.io/en/latest/sensor-msgs.html#sonar
.. _nao_sensor_msgs::msg::Touch: https://nao-interfaces-docs.readthedocs.io/en/latest/sensor-msgs.html#touch

.. _nao_command_msgs::msg::JointPositions: https://nao-interfaces-docs.readthedocs.io/en/latest/command-msgs.html#jointpositions
.. _nao_command_msgs::msg::JointStiffnesses: https://nao-interfaces-docs.readthedocs.io/en/latest/command-msgs.html#jointstiffnesses
.. _nao_command_msgs::msg::ChestLed: https://nao-interfaces-docs.readthedocs.io/en/latest/command-msgs.html#chestled
.. _nao_command_msgs::msg::LeftEyeLeds: https://nao-interfaces-docs.readthedocs.io/en/latest/command-msgs.html#lefteyeleds
.. _nao_command_msgs::msg::LeftFootLed: https://nao-interfaces-docs.readthedocs.io/en/latest/command-msgs.html#leftfootled
.. _nao_command_msgs::msg::RightEyeLeds: https://nao-interfaces-docs.readthedocs.io/en/latest/command-msgs.html#righteyeleds
.. _nao_command_msgs::msg::RightFootLed: https://nao-interfaces-docs.readthedocs.io/en/latest/command-msgs.html#rightfootled
.. _nao_command_msgs::msg::HeadLeds: https://nao-interfaces-docs.readthedocs.io/en/latest/command-msgs.html#headleds
.. _nao_command_msgs::msg::LeftEarLeds: https://nao-interfaces-docs.readthedocs.io/en/latest/command-msgs.html#leftearleds
.. _nao_command_msgs::msg::RightEarLeds: https://nao-interfaces-docs.readthedocs.io/en/latest/command-msgs.html#rightearleds
.. _nao_command_msgs::msg::SonarUsage: https://nao-interfaces-docs.readthedocs.io/en/latest/command-msgs.html#sonarusage
