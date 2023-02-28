# bashScripts
This repo contains the various bash scripts that I have/will written/write that I create to make my life easier
Feel free to use them if you want, but I won't provide support

Since I wrote these for personal use, there's almost no error checking, so I'll have to write instructions on what each one does and how to avoid errors, but I'll do that later

To use/install any of them:
Download the script you want to use
Open a terminal in the same directory and run: chmod +x <script name>
Then place the script in the root/usr/bin directory
Finally, type the name of the script into the terminal and it will execute

The protonUpdate one doesn't seem to be working properly. It puts the files in the appropriate place as far as I can tell, but steam doesn't see the options after running it

Script Descriptions:
aptFix - fixes broken installs in apt for ubuntu based systems
dpkgFix - resets dpkg config to fix issues with apt installs
gdmenuGenerator - creates the folder structure for a gdemu optical drive emulator for dreamcast, only works with cdi files currently
gdmenuList - creates a text file displaying the contents of a gdemu folder structure for easier troubleshooting
protonUpdate - downloads the latest verseion of Steam GE Proton and places it in the appropriate folder to use with steam
update - updates apt repositories, upgrades apt installed software, removes any unnecessary packages, and updates flatpak software