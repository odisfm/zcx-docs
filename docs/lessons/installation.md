# installing zcx

Installing zcx is super easy.

## get a distribution

A 'distribution' is what we call a finished release of a zcx script. It contains the 'core' of zcx, along with hardware-specific code that makes it work with your controller. 

[Click here to see the latest release for all maintained hardware.](https://www.github.com/odisfm/zcx-core/releases/latest)

### my hardware isn't listed 💔

No problem. Have a look at the [zcx-core discord server](https://discord.gg/DCtbuEe8Qr) to see if there is a pre-alpha version available. There may be a distribution ready to go, that just needs someone who actually owns the hardware to confirm it works. And if there isn't, feel free to put in a request for your hardware!

## install the script

Each distribution comes as a .zip file. Unzip that file, and you'll see a folder with the same name. This is the 'root' folder of this zcx distro. You can rename the folder to whatever you like, and that's the name that shows up in Live's preferences. We include a leading underscore, because that should push it to the top of the control surface list. Feel free to remove it.

For our purposes, zcx functions like any other control surface script, so you should [follow the Live manual's instructions](https://help.ableton.com/hc/en-us/articles/209072009-Installing-third-party-remote-scripts) for that.

## load the script

When you assign the script to a slot in Live's preferences, the script automatically loads.

You should set the MIDI in and out ports to the relevant hardware before assigning the script to a slot.

At this point, you may need to [reload the script](/docs/lessons/reloading-control-surfaces.md).

### if your controller has a distinct 'user mode'

Many controllers, such as the Push and Launchpad have a 'Live' mode and a 'user' mode. If you have officially supported hardware, zcx should automatically handle switching the controller's mode. If it doesn't, [raise an issue](/docs/lessons/reporting-bugs.md).

## explore! 🌏

Your zcx distribution comes with a carefully crafted demo config, put together by the maintainer for your hardware. It's designed to give a taste of zcx's capabilities out of the box, and be intuitive to edit. Once you're done with that, continue with this tutorial. :)

___

[Back to tutorial chapter](getting_started.md)
