# BrightSign-Companion-App

## Overview
This script is designed to accompany the BrightSign Plug-In for the Q-SYS Ecosystem, following the set-up guide provided in the Plug-Ins helpfile. It is designed to bypass the need to do any programming in BrightAuthor and allow you to trigger videos with a single button press and dictate whether those video files will play once, loop and also include an optional (and probably preferable) default video loop. Allowing for easier automations of your video content which can be used for digital signage playlists, holding screens or show reels.

## Set-Up
1. You will want to load in the auto.brs file that is provided with the BrightSign plug-in (or from this repository) to the SD card of your BrightSign player to allow it to easily connect to the plug-in. (See Help File PDF)
2. You will also want to make sure you have valid video files loaded onto the SD card too. 
3. Once installed verify the plug-in is configured correctly and is successfully initialised to the BrightSign player. Once verified, we're ready to load in the Companion script.
4. You will need to enable 'Script Access' to the BrightSign plugin. Set the Script Access to either 'All' or 'Script'. You can also give it a 'Code Name' too for easy identification (recommended).
![image](https://github.com/user-attachments/assets/1ac95f7b-8827-4968-90af-d7a03e5703e1)

5. Bring in the BrightSign Companion script and load the Design to your Core. This will also work in Emulation mode for testing purposes.
![image](https://github.com/user-attachments/assets/3a85e78a-8948-47cc-bd5d-bcee0c8878c7)

6. Once the Design is running, open the BrightSign Companion script and you will be prompted to select your BrightSign in the dropdown box below. Pick the one you wish to control.
![image](https://github.com/user-attachments/assets/91d483eb-7d28-401d-a01e-0a667fcf8063)

7. If successful, you should see the UI populate with the video files from the playlist - and you're ready to go!
![image](https://github.com/user-attachments/assets/be364810-c0ad-49e2-b963-10c22738f200)

## Usage
The goal here is to streamline the programming of scheduling video playlists, by referncing the video trigger buttons either from a UCI or maybe automating it with other aspects of your Q-SYS Control system. No need for any additional programming in other software!

### Playing content
1. To play a video, simply hit one of the File Name trigger buttons in the UI and this will load the file and begin playing.
2. If you wish to loop a particular video then simply toggle the corresponding loop button for that video trigger.
![image](https://github.com/user-attachments/assets/bd2397bb-754c-4438-b349-f695189df260)

### Default Home Fallback
If a video is not looping, once it ends, the default state of the BrightSign is to just stop playing video. If you would like it to return to a particular video such as a holding screen or whatever else you may like then it is recommended to enable this feature.

1. Select the video file you want to be your default fallback video
2. When a BrightSign is connected, it will automatically grab the first file in the playlist (in alphanumerical order)
3. Hit the enable button and when the BrightSign goes 'idle' it will automatically loop this selected video
4. There is also a reset button which will manually force this loop to begin if you need a quick 'return home' function
![image](https://github.com/user-attachments/assets/92f87166-98d6-4926-b274-8a40e1963dbe)

#Additional Information
## Solution Type: 
Control

## Product Category:
Information Technology

## Tested On:
Q-SYS Designer v9.10.2
BrightSign Plug-in v1.1.0

## Support
This script is a companion tool developed by myself to make integrating automations with the BrightSign plug-in easier for the applications I have needed it for. It is not intended to be an official addition to the BrightSign plug-in and therefore will not qualify for official support from Q-SYS. 
This is an open source tool, and I would encourage anyone to give it a try and tweak it for their needs as they see fit. If you have any cool additions you would like to add I would encourage you to do so and submit a pull request to add to this repository.

Happy programming! 🚀
