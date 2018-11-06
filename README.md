# Wireshark profile for LTE traffic capture and analysis

## General

This repository provides a Wireshark configuration profile that allows the user to capture and analyze LTE (Long Term Evolution) traffic.

Clone or download the project to obtain a .ZIP with the configuration profile.

After you have downloaded it, unzip it. You will see a folder named **LTE** with several files inside it. This folder contains the profile itself.

## Installation instructions

First, you need to locate your Wireshark profiles directory. The path to this directory may vary, depending on your operating system.

#### Windows systems

In Windows systems, the profiles directory is inside the installation directory. This directory should be placed in the following path: 
```
C:\Program Files\Wireshark\profiles
```
If the **profiles** directory is missing, create it.

Once you have located this directory, open it with the file explorer and move here the **LTE** directory mentioned earlier. Once completed, the installation is done.

#### UNIX-like systems

The profiles directory in UNIX-like systems should be located in the following path:
```
/usr/share/wireshark/profiles
```
If the **profiles** directory is missing, create it.

On macOS systems, the profiles directory is most likely to be located in the following path:
```
/Users/your_username/.wireshark/profiles
```
Again, if the **profiles** directory is missing, create it.

Once you have located this directory, open it with the file explorer and move here the **LTE** directory mentioned earlier. You can also use a terminal, and the command may need sudo privileges. Once completed, the installation should be done.

**NOTE: If you do not find the directory mentioned on your system, or if you have found another directory which can be valid, please open an issue and notify it. In UNIX-like systems the profiles directory path vary and might not be the same in different machines. Thank you :)**

## Activation instructions
The profile needs to be activated to use it.

Open the Wireshark application. Click on **Edit** --> **Configuration profiles**. A new dialog should appear, listing all the current configuration profiles that are installed. If the installation was successful, a **LTE** name should appear in the list. To activate the profile, simply select it by clicking on its name. Once selected, click on the **OK** button. The dialog should close and the profile should be activated.

The activation can take some time, specially if you have opened a capture file.

You can check that the profile is activated by looking at the lower right corner of the Wireshark GUI, in the application status bar. It should appear the following:
```
Profile: LTE
```
