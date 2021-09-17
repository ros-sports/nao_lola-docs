Installation
############

.. note::

    Instructions here assume that you are **on the NAO**, and in a ROS2 workspace
    root directory.

Binary Installation
*******************

The package is released only for ROS2 galactic, following instructrions below to install the debian binary package:

.. code-block:: console

   sudo apt update
   sudo apt install ros-galactic-nao-lola

Source Installation
*******************

Cloning repositories
====================

In your ROS2 workspace, clone the repository:

.. code-block:: console

   git clone --recursive https://github.com/ijnek/nao_lola.git src/nao_lola
   vcs import src < src/nao_lola/dependencies.repos

Building
========

To build the package and its dependencies, in the workspace root directory, run:

.. code-block:: console

   colcon build
