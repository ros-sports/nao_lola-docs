NAO Setup
#########

.. warning::

    This package requires you to have access to an **opn file with root access**,
    which Softbank has granted access only for RoboCup SPL teams. If you are a member
    of a RoboCup team, contact the Technical Committee of SPL to get a copy.

Install Ubuntu20.04 on NAO
**************************

The tested way to run ROS2 on the Nao, is to run Ubuntu20.04 on the Nao.

Download NaoDevils' `NaoImage`_ project, and set your NAO up to use Ubuntu20.04.

.. note::

    Instructions are provided in the `README.md` of `NaoImage`_

Install ROS2 on NAO
*******************

Follow `Installing ROS 2 via Debian Packages`_, to install ROS2 from debian packages.
Do a **ROS-Base Install**, to prevent downloading unnecessary GUI packages.

.. note::

    In the `Install ROS 2 package`_ step, do a **ROS-Base Install**, rather than a *Desktop Install*

.. _NaoImage: https://tu-dortmund.sciebo.de/s/8bg5NQJ5Gm1j30z
.. _Installing ROS 2 via Debian Packages: https://docs.ros.org/en/galactic/Installation/Ubuntu-Install-Debians.html
.. _Install ROS 2 package: https://docs.ros.org/en/galactic/Installation/Ubuntu-Install-Debians.html#install-ros-2-packages
