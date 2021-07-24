Installation
############

.. note::

    Instructions here assume that you are **on the NAO**, and in a ROS2 workspace
    root directory.

Cloning repositories
********************

In your ROS2 workspace, clone the repository:

.. code-block:: console

   git clone --recursive https://github.com/ijnek/nao_lola.git src/nao_lola
   vcs import src < src/nao_lola/dependencies.repos

Building
********

To build the package and its dependencies, in the workspace root directory, run:

.. code-block:: console

   colcon build
