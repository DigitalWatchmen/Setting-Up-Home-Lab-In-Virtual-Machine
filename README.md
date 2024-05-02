# Setting-Up-Home-Lab-In-Virtual-Machine

Downloaded Debian 12.5.0 64 bit ISO file

Created virtual machine running Debian (SecLab) with the following specs:
Base Memory -  4096MB
Processors - 4
Video Memory - 16MB
Virtual Disk Image - 20GB

Adding user 'seclab' into sudoers file through CLI:

#Switch to root user
su root

#Add user 'seclab' into sudo group
adduser -aG sudo seclab

#Verifying that 'seclab' has been added to group sudo
getent group sudo

