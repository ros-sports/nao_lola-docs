NAO ROS2 Setup
##############

.. warning::

    This package requires you to have access to an **opn file with root access**,
    which Softbank has granted access only to RoboCup SPL teams. If you are a member
    of a RoboCup team, contact the SPL Technical Committee to get a copy.

The easiest way use ROS 2 on the Nao is to use an Ubuntu 22.04-based image for the NAO, and use the apt package manager to install ROS 2 binaries.

Install Ubuntu22.04 on NAO
**************************

Follow instructions provided by NaoDevils' `NaoImage`_ to set up Ubuntu 22.04-based on the NAO.

Install ROS2 on NAO
*******************

Follow `Installing ROS 2 via Debian Packages`_, to install ROS2 from debian packages.
Do a **ROS-Base Install**, to prevent downloading unnecessary GUI packages.

.. note::

    In the `Install ROS 2 package`_ step, do a **ROS-Base Install**, rather than a *Desktop Install*.

.. _NaoImage: https://tu-dortmund.sciebo.de/s/8bg5NQJ5Gm1j30z
.. _Installing ROS 2 via Debian Packages: https://docs.ros.org/en/galactic/Installation/Ubuntu-Install-Debians.html
.. _Install ROS 2 package: https://docs.ros.org/en/galactic/Installation/Ubuntu-Install-Debians.html#install-ros-2-packages
