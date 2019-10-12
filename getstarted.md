WPI has deprecated Eclipse and started pushing **Visual Studio Code** as the new standard IDE. WPILib site updated the instruction on following page:

[https://wpilib.screenstepslive.com/s/currentCS/m/getting_started/l/999999-installing-c-and-java-development-tools-for-frc](https://wpilib.screenstepslive.com/s/currentCS/m/getting_started/l/999999-installing-c-and-java-development-tools-for-frc)

A key improvement of the setup process this season is that a single "one-stop-shop" WPILib Installer replaces previous multi-step manual process, and takes care of all the software pieces needed for FRC programming.

Following is a summary of the steps to follow:

1. Go to [https://github.com/wpilibsuite/allwpilib/releases](https://github.com/wpilibsuite/allwpilib/releases), download either WPILibInstaller_Windows64-2019.1.1.zip (for 64-bit Windows) or WPILibInstaller_Windows32-2019.1.1.zip (for 32-bit Windows). To determine your Windows version, go to **Control Panel** and open **System**, look for "System type" field. The file is over 1 GB, it will take some time. Save the downloaded file to a local folder.

2. The downloaded zip file contains only a single file with same name but .exe file extension, extract it to a the same folder, double-click it to start the installation. To extract the file, right-click it and choose 'Extract All'.

3. The installer will initially have the two checkboxes "Visual Studio Code" and "Visual Studio Code Extensions" disabled (see below). You need to click "Select/Download VS Code" button to download it first. The downloaded file is **OfflineVsCodeFiles-1.30.1.zip** and will be placed in the same folder as the installer. Leave it there and don't open it.

![WPILib Installer VSCode](https://raw.githubusercontent.com/team7587/FRC2019/master/resources/img/wpilib-install-vscode.PNG)

4. Back on WPILib Installer, check the two "Visual Studio Code..." checkboxes, and click "Execute Install" to start the full installation process. After a while you'll get a prompt confirming the installation is completed, and see below 3 icons placed on the desktop.

![WPILib Installer Done](https://s3.amazonaws.com/screensteps_live/image_assets/assets/002/027/165/original/908ac47e-8564-4119-988c-39fb30fe7389.png)

![WPILib Installer Icons](https://raw.githubusercontent.com/team7587/FRC2019/master/resources/img/wpilib-install-done.PNG)

5. Double-click the icon "FRC VS Code 2019" to launch the IDE, type **Ctrl+Shift+P**. A command pallet shows up on the top, type in "WPILIb" and you should see a list of WPILib commands show up. This confirms that the installation is successful.

**Note** that all the files installed by the installer are placed the folder **C:\Users\Public\frc2019**.
