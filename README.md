# Linux Ambient Backlight
### Ambient Backlight?
This is a simple project building upon the efforts of hackan301 to bring MacOS-esque ambient brightness control to Linux. 
I have found GNOME's implementation too jarring, and KDE does not have this facility yet - so this program interfaces directly with the sensors and updates the backlight.
Here is a link to the original project: https://store.kde.org/p/1259771/

### Installation
Just run the ```AmbientLightFix_RunME.sh``` file which will automatically detect and enable the correct script!
Alternatively, you can copy the respective shell script to /usr/bin, and the corresponding service file to /etc/systemd/system (on Arch + derivatives - may be different for other distributions), and run:
`$ sudo systemctl enable ambientLightFix_xxx`
`$ sudo systemctl daemon-reload`

### Issues?
This project will be worked on quite extensively. I plan to port this to C# and compile as binaries, and add extra functionality like calibration and keyboard brightness control. 
Please feel free to contribute and suggest new features and ideas!
