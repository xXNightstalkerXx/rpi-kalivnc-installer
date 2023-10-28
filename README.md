## DEPRECIATED (Debian Bullseye)
# rpi-kalivnc-installer
This Repository has some bash Scripts in it that download and setup the neccessary Files for the X11VNC Server on RPI Kali Linux.
The Installer creates a new Directory where this Repository get's downloaded into.

After downloading the necessary Files it will setup the VNC Server and ask you for a Password to secure your VNC Server.

The Installer also creates a backup of the /home/kali/.vnc/xstartup File before changing them.
When launching the uninstall Script the /.vnc Folder will get deleted again

I'm not an expert Coder so use this Repo on your own Risk and don't blame me if you have to reinstall your Raspberry.

If you find something interesting within my Scripts feel free to copy parts of it and implement it into your own code.
Also feel free to contribute to this Repository and make it better :)


----------------------------------------------------------------
----------------------------------------------------------------
# INSTALLATION

    wget https://raw.githubusercontent.com/xXNightstalkerXx/rpi-vnc-installer/Debian_Bullseye/rpi-vnc-installer
Download the Kalivnc Installer Script with wget

    sudo chmod 0755 rpi-kalivnc-installer
Make the file executable

    ./rpi-kalivnc-installer
Launch the Installer Script
</br>
</br>
The Installer does the rest of the Job for you now.

----------------------------------------------------------------
----------------------------------------------------------------
# HOW TO USE

After Installation your VNC Server will spin up automagically after every boot. </br>
To connect just type the IP-Adress of your Kali Pi into your VNC Viewer followed
by a ":1" </br>
You will also need the Password you entered during Installation to connect. </br>
</br>

    rpi-kalivnc-uninstaller
Will revert all changes made to your system.
Also delete's all associated Files.
</br>
</br>
</br>
ATTENTION!!</br>
DO NOT install Kali VNC with the RPI-KALIVNC-AUTOINSTALLER and use the RPI-KALIVNC-INSTALLER instead!!</br>
The RPI-KALIVNC-AUTOINSTALLER is just meant to be used by my RPI-SETUP-TOOL!</br>


----------------------------------------------------------------
----------------------------------------------------------------
