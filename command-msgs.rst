.. _command_msgs:

Command Msgs
############

The package **nao_lola_command_msgs** defines msgs used to send commands to the underlying
NAO hardware.

.. _command_joints:

Joints
******

.. _command_joint_positions:

JointPositions
==============

By being able to specify the indexes, we can have different nodes sending
partial joint position commands.

.. code-block:: python

    # Message to specify positions for the NAO's motor joints.
    #
    # Each joint is uniquely identified by its index (See JointIndexes.msg)
    #
    # The two arrays in this message should have the same size, where the first item
    # in indexes, corresponds to the first item in positions, etc.

    uint8[] indexes  # See JointIndexes.msg (eg. JointIndexes::HEADYAW)
    float32[] positions # radians

.. _command_joint_stiffnesses:

JointStiffnesses
================

By being able to specify the indexes, we can have different nodes sending
partial joint stiffness commands.

.. code-block:: python

    # Message to specify stiffnesses for the NAO's motor joints.
    #
    # Each joint is uniquely identified by its index (See JointIndexes.msg)
    #
    # The two arrays in this message should have the same size, where the first item
    # in indexes, corresponds to the first item in stiffnesses, etc.

    uint8[] indexes  # See JointIndexes.msg (eg. JointIndexes::HEADYAW)
    float32[] stiffnesses  # 0.0 - 1.0

.. _RGB Leds:

RGB Leds
********

Msgs that use `std_msgs/ColorRGBA`_ to specify colors for the RGB LEDs.

.. note::

    **Expect ranges for R, G and B are 0.0 - 1.0. The alpha value (A) is ignored.**

.. _ChestLed:

ChestLed
========

A single RGB led in the chest.

.. code-block:: python

    std_msgs/ColorRGBA color  # r, g, b should be 0.0 - 1.0. a is ignored

.. _sensor_LeftEyeLeds:

LeftEyeLeds
===========

See :ref:`left_eye_leds` to see which indexes correspond to which led.

.. code-block:: python

    std_msgs/ColorRGBA[8] colors

.. _sensor_LeftFootLed:

LeftFootLed
===========

A single RGB led in the left foot.

.. code-block:: python

    std_msgs/ColorRGBA color

.. _sensor_RightEyeLeds:

RightEyeLeds
============

See :ref:`right_eye_leds` to see which indexes correspond to which led.

.. code-block:: python

    std_msgs/ColorRGBA[8] colors

.. _sensor_RightFootLed:

RightFootLed
============

A single RGB led in the right foot.

.. code-block:: python

    std_msgs/ColorRGBA color


.. _blue_leds:

Blue Leds
*********

Msgs that specify intensity of the blue leds.

.. _sensor_HeadLeds:

HeadLeds
========

See :ref:`head_leds` to see which indexes correspond to which led.

.. code-block:: python

    float32[12] intensities  # 0.0 - 1.0

.. _LeftEarLeds:

LeftEarLeds
===========

See :ref:`left_ear_leds` to see which indexes correspond to which led.

.. code-block:: python

    float32[10] intensities  # 0.0 - 1.0

.. _RightEarLeds:

RightEarLeds
============

See :ref:`right_ear_leds` to see which indexes correspond to which led.

.. code-block:: python

    float32[10] intensities  # 0.0 - 1.0

.. _SonarUsage:

SonarUsage
**********

Command to tell Lola whether to enable/disable the sonar.

.. code-block:: python

    bool left  # Set to true, to use left sonar
    bool right  # Set to true, to use right sonar

.. _std_msgs/ColorRGBA: http://docs.ros.org/en/api/std_msgs/html/msg/ColorRGBA.html
