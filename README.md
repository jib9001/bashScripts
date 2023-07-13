# bashScripts
This repo contains the various bash scripts that I have/will written/write that I create to make my life easier.
These scripts are designed to work for ubuntu based distros, such as ubuntu, linux mint, pop_os, elementary_os, etc.

## Intallation:
You can install all of the scripts by running the install script as super user

### Navigate to the folder containing the scripts and then execute the following command:
``` sudo ./install.sh ```

### To install individual scripts:
Download the script you want to use
Open a terminal in the same directory and run: 
``` chmod +x <script name> ```

Then place a copy of the script in the /bin directory
You can do this with the following command: 
``` sudo cp <script name> /bin ```

## Usage:
After installation, just type the name of the script into the terminal and it will run

## Script Descriptions:
* aptFix - fixes broken installs in apt for ubuntu based systems
* dpkgFix - resets dpkg config to fix issues with apt installs
* gdmenuGenerator - creates the folder structure for a gdemu optical drive emulator for dreamcast, only works with cdi files currently
* gdmenuList - creates a text file displaying the contents of a gdemu folder structure for easier troubleshooting
* protonUpdate - downloads the latest verseion of Steam GE Proton and places it in the appropriate folder to use with steam
* update - updates apt repositories, upgrades apt installed software, removes any unnecessary packages, and updates flatpak software