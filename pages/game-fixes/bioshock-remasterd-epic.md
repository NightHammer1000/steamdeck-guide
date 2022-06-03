# Bioshock Remastered from the Epic Shop

The Epic Store Version of the Bioshock Remastered Collection currently comes with the 2K Launcher.
Sadly, this 2K Launcher is totally broken in Wine and Proton.
To get these three games to work requires a Workaround.

## Using Heroic Games Launcher

The Heroic Games Launcher is an Open-Source Reimplementation of the Epic and GOG Launcher. 
It allows you to Download and Install Epic and GoG Launcher Games without the need of running these two Launchers in Wine.
It also brings a lot of cool and useful troubleshooting options with it.

#### Installing Heroic Games Launcher

This can be done in **Desktop Mode** by either **Console** or the **Discovery Store**
The Console Command for installing the Heroic Game Launcher is:

`flatpak install flathub com.heroicgameslauncher.hgl`

Now we also need a few other things  to get our Games Running.

1. Open Heroic Games Launcher
2. Go to Wine Manager in the Bottom-Left Corner
3. Install the latest Version Proton-GE
4. Under Settings → Wine, set the Wine Version to the newly Downloaded Proton-GE

#### Install the Games

Now simply install the Games through the Heroic Launcher.

**Be sure to make a note of the Installation Path!**

We are going to need that later on!

But don't try to start them once they are finished. There are still a few steps we need to take.

Repeat these Steps for all 3 Games:

1. Click the Small Gear Icon that appears when you hover the Cursor over the Game Icon.
2. Disable ESYNC and FSYNC. This fixes the very slow loading of Textures in these Games
3. Set Wine Version to the downloaded Wine-GE Version if it isn't already.
4. On the Left Side of the Window, under Settings, click on "Other"
5. Under "Select an Alternative EXE to run" navigate to the earlier noted Install Folder and select the Game's Executable.

#### Start the Game

Now you can simply start the Game through the Heroic Launcher!

#### Troubleshooting

It is sometimes necessary to install the Prerequisites.

These can be found under **"Build/FinalEpic/Prerequisites"**

You can run **"Prerequisite Installer.exe"** with the "Run EXE in Prefix" function found under the Games Settings. (The Small Gear Icon that appears when you hover the Cursor over the Game Icon)

There will be nothing on-screen if you do this. Just wait 5 Minutes and you should be good to go.

Sometimes it can happen that Bioshock will throw an Error Message telling you to start the Game through Epic Launcher. 
If that happens, just start the Game again.
