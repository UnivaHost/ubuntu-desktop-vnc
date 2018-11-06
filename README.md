# ubuntu-desktop-vnc
How To Install A Desktop And VNC On Ubuntu 16.04


#1
## Update your system using the following command.
> sudo apt-get update && sudo apt-get upgrade -y

#2
## Install Ubuntu Desktop on Your Instance
> sudo apt-get install ubuntu-desktop gnome-panel gnome-settings-daemon metacity nautilus gnome-terminal


#3
## Install and Configure a VNC Server
> sudo apt-get install vnc4server


#4
## Now test the VNC server by starting a session.
> vncserver :1


#5
> vncserver -kill :1
