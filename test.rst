Prepare your workstation computer
=================================

Before Installing Phoenix...
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
It is strongly recommended to complete the base installation of FRC tools.
https://wpilib.screenstepslive.com/s/currentCS/m/getting_started/l/144981-frc-software-component-overview

.. warning:: You will need to image the roboRIO to 2019 software before continuing.  The **roboRIO** kickoff versions are **image 2019_v12 and firmware 6.0**.

Test base FRC Installation - FRC LabVIEW
----------------------------------------------------------------------------------
If a team intends to use LabVIEW to develop robot software, be sure to complete the full NI installer.  At which point, opening LabVIEW should reveal the FRC-styled graphical start menu.

At this point it is recommended to create a simple template project and test deploy to the roboRIO.  Be sure the DriverStation can communicate with the robot controller, and that DS message log is functional.

.. note:: LabVIEW is versioned 2018 due to its release schedule. Therefore, LV2018 is used for the 2019 season.

Test base FRC Installation - FRC C++ / Java
----------------------------------------------------------------------------------
It is recommended to install the FRC Driver Station Utilities. This will install the Driver Station software, which is necessary for:

1. Basic comms checks
2. Reading joystick data
3. Generally required for enabling motor actuation (Phoenix Tuner provides an alternative).
