# Installation

Begin the install process by running `install-polaris`.

Then select your language. If you are reading this you probably know English (because as of writing this originally, there are no translations)

Next go to timezone and select your timezone.

Next go to Mirrors. Go to Mirror regions and just select your country. If you are in the US you can probably just ignore this.

Next go to disk configuration. Most likely you'll wanna choose these:

Partitioning - Use a best effort partitioning layout - Choose your drive - BTRFS - Yes - Use compression

Then go back.

If you are wondering why LVM isn't an option, It's because support for this is so nonfunctional that not even Emergency mode works properly. It literally can't mount the rootfs with encryption.

For disk encryption, what do you got things to hide? Are you a criminal? Just kidding. But the average Joe might not need this.

Next go to hostname and type in anything. Nobody cares.

Now set the root password (if you don't see anything that's normal)

Now make a new user, preferably with sudo perms. You can make a few, hell if I care.

Now hit install and wait, get some coffee, go outside, touch grass, etc.

Once the installation is done, reboot.

Congrats! The installation is done.

Move onto here, optionally: [Post Installation](https://polaris-linux-distro.github.io/handbook/PostInstallation) 
