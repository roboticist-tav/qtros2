# qtros2
Repository for examples and tutorials of [QT](https://en.wikipedia.org/wiki/Qt_(software)) [GUI](https://en.wikipedia.org/wiki/Graphical_user_interface) development for [ROS2](https://index.ros.org/doc/ros2/) interaction.

## Requirements
To use qtros2 you will need a [PC](https://en.wikipedia.org/wiki/Personal_computer) with the following:

-	**Operating System: Ubuntu 18.04.3 LTS**

You will need the latest LTS version of Ubuntu, so far, the latest version tested with qtros2 is the desktop version 18.04.3 LTS (Bionic).  See https://ubuntu.com/download/desktop to download the [ISO Image](https://en.wikipedia.org/wiki/ISO_image). You should then use [Rufus](https://rufus.ie/) to install from a [USB drive](https://en.wikipedia.org/wiki/USB_flash_drive).

-	**Robot Operating System: ROS2 Dashing Diademata**

You will then need ROS2 installed.  It is recommended to follow the instructions for installing ROS2 via Debian Packages found at: https://index.ros.org/doc/ros2/Installation/Dashing/Linux-Install-Debians/. 

To check which ROS2 version (distro), use the following at the command prompt:
```
echo $ROS_DISTRO
```

## Setting Up
To set up the environment to develop a GUI in ROS2 (qtros2) you will need to install the following (in order):

-	**QT Plugin: ROS Qt Creator Plug-in**

The Qt Creator Plugin has been created to use QT Creator as an [IDE](https://en.wikipedia.org/wiki/Integrated_development_environment) of a ROS2 workspaces rather than for ROS2 GUI development.  However, the ROS Qt Creator Plugin is needed. To set-up the plugin follow the user installation instructions at: https://ros-qtc-plugin.readthedocs.io/en/latest/_source/How-to-Install-Users.html.

After several tests it appears that it is best to install the ROS Qt Creator Plugin ***before*** instaling QT.

- **IDE: QT**

You will next need to download QT, so use the installer provided at: https://www.qt.io/download.

## Installing qtros2

It is recommmended to install the complete respository of qtros2 on to your PC and pick and choose parts you require for your project(s) on your PC.

### Create a QTROS2 workspace

Open a terminal window on your PC (use Ctrl+Alt+T) at the command prompt create a workspace directory structure:
```
mkdir -p qtros2_ws/src
cd ~/qtros_ws/src
```

### Clone (Download) QTROS2 Repository

Still at the command prompt in the terminal window, enter the following:
```
git clone https://github.com/roboticist-tav/qtros2.git
```

If you get any errors at this point, here is how they are resolved...

| Error | Reason | Solution |
| --- | --- | --- |





