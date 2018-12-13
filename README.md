# IP Camera Emulator Std
Prebuilt Win32 binaries of IP Camera Emulator (Standard)

Note you will need to make a copy of the following files from the (32-bit) VLC application folder and place them in the same folder as the IpCameraEmulatorStd binaries,

* libvlc.dll
* libvlccore.dll
* the entire "plugins" folder

The ones from VLC version 2.2.6 and 1.1.9 seem to work well.

The app requires .Net Framework 4 or higher. App settings are maintained in C:\ProgramData\IpCameraEmulator\ and read/write access to this folder is required.

More details can be found at https://inspiredtechnologies.wordpress.com/2018/11/24/an-ip-camera-emulator/
