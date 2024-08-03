# Post Installation

Once you have logged in, you'll probably wanna do these things:

## Install applications

Start by opening the terminal (not as root) and running 

`polo-pkg update`

to synchronize all your packages. Now you can run

`polo-pkg install steam`

to install Steam.

## Add pretty name to users

Open up the Budgie Control Center and go to the Users section.

Now unlock the settings and press the pencil. Now type in a new name.

## Timeshift

Timeshift is a backup utility. Open the menu and search for Timeshift.

Then in the wizard, select the backup type. If you are on BTRFS then use BTRFS snapshots, or use RSYNC. Depends.
Select your disk, snapshot level (preferably weekly or daily) and preferably backup user home dirs.

Congratulations! You have finished installing Polaris Linux with the whole guide.

Optionally if you wanna get a screenshot to showoff to your friends run

`about-polaris` to get the system stats.
