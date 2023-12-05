NAO ROS2 Setup
##############

.. warning::

    This package requires you to have access to an **opn file with root access**,
    which Aldebaran has granted access only to RoboCup SPL teams. If you are a member
    of a RoboCup team, contact the SPL Technical Committee to get a copy.

The easiest way use ROS 2 on the NAO is to flash an Ubuntu 22.04-based image on the NAO, and use apt to install ROS 2.

Flash RoboCup OPN file
**********************

.. note::

    If you have a NAO robot with the robocup-opn image already flashed, skip this step and continue
    to the `Install Ubuntu22.04 on NAO`_ step.

.. tip::

    This step is necessary to prevent motorboard firmware issues, where the robot cannot read/write
    the joint positions, that may arise if the robot is not flashed with the robocup-opn image
    before flashing the Ubuntu based image.

Flash the NAO with the **robocup-opn** file if it is:

* brand-new
* returned from manufacturer (that has been reflashed with the default image)
* not flashed with the robocup-opn file

To flash a NAO with the robocup-opn file, you must:

* `Create NAOqi USB`_, then
* `Flash the NAO`_

Create NAOqi USB
================

#.  Follow the instructions on
    `Manufacturer's Documentation <http://doc.aldebaran.com/2-1/software/naoflasher/naoflasher.html>`_

    .. note::
        The 2.1 flasher also works with the 2.8 opn.  You can also just use dd on linux and mac.


Flash the NAO
=============

To flash the robot, run

#. Turn off the NAO
#. Insert the USB stick into the back of the robots head
#. Press and hold down the chest button on the NAO until it lights up blue
#. Wait until it says ``Ognak gnuk!`` and starts looking around

Install Ubuntu22.04 on NAO
**************************

Follow instructions provided by NaoDevils' `NaoImage`_ to set up Ubuntu 22.04-based on the NAO.

Install ROS2 on NAO
*******************

Follow `Installing ROS 2 via Debian Packages`_, to install ROS2 from debian packages.
Do a **ROS-Base Install**, to prevent downloading unnecessary GUI packages.

.. note::

    In the `Install ROS 2 package`_ step, do a **ROS-Base Install**, rather than a *Desktop Install*.

.. _NaoImage: https://github.com/NaoDevils/NaoImage
.. _Installing ROS 2 via Debian Packages: https://docs.ros.org/en/galactic/Installation/Ubuntu-Install-Debians.html
.. _Install ROS 2 package: https://docs.ros.org/en/galactic/Installation/Ubuntu-Install-Debians.html#install-ros-2-packages
