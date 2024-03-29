.. Nao Lola documentation master file, created by
   sphinx-quickstart on Wed Jul 14 15:56:37 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Nao Lola
========

This project consists of  ROS2 packages that allow communicating with the
NAO's RoboCup-tailored Lola middle-ware.

It serves two purposes:

* receive sensory information from Lola, splits them up and broadcast them on separate ROS2 topics
* subscribe to certain ROS2 topics to compose an effector message and send it to Lola

The project is hosted on `Github`_.

.. toctree::
   :hidden:
   :maxdepth: 2

   nao-ros2-setup
   installation
   lola-client
   sensor-msgs
   command-msgs
   leds
   joints
   related-ros2-packages


.. _Github: https://github.com/ros-sports/nao_lola
