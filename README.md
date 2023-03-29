# arch-install
This is a collection of scripts to help automate the installation and configuration of the tools and applications I like to use.


## Before Installation
Before starting the install process, you may want to prevent the sudo password prompt from timing out.
To do this, first install a text editor. I'll use neovim for example. Then do:

sudo EDITOR=nvim visudo # Replace nvim with other text editor

Add the following line at the bottom of the file:

Defaults passwd_timeout=-1


Once this is done, reboot your machine and begin with the installation instructions below.


## Installation
Execute the shell scripts in order. Follow any instructions given in each script.
