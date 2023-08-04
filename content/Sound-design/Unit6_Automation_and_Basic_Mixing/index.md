# Unit 6 Automation and Basic Mixing

Here we will start introducing the idea of audio mixing: combining various audio files into a cohesive, balanced, single product. We have already explored adjusting the volume of a track, and here we will start experimenting with techniques like panning and crossfades in order to arrange your sounds and create new textures, followed by going over automation. Automation allows for you to program parameters to set themselves and change automatically over the course of a song; something super useful for maintaining balance through different sections of music!

## Audio Loops

Studio One 6 comes with a large number of loops that can be utilized in your projects. These vary between audio files and MIDI data, but can both be easily dropped into a session for quick implementation. Keep in mind however that these can take up a large amount of storage space, so you may not be able to fit many on your computer. A few projects in this class will want you to utilize the loops, while others will specifically forbid it. While practicing and learning, having an easily repeatable loop is useful for comparing your changes and fine-tuning balances.

To find a loop, open the Browse window and go to the “Loops” tab. Here your installed loops are broken up first by style, then by instrument. Some collections may have further organization allowing you to navigate to a specific kind of loop while others stop at this level. To preview a loop click on it and you will see information about it appear at the bottom of the Browse panel. Press the play button to preview the loop. If adding a loop to the content it is important to check the tempo and key (if applicable) in order to make sure that there are no problems with the other content. You can manually change the loop’s tempo or transpose it to a different key, but the sound may change to no longer match what you are looking for, so be sure to listen both before and after! To use the loop, simply drag it into the desired track in your session. The loop will then act like any other audio or MIDI event.

## Audio Panning

When arranging sounds, you can control whether they come out of the left speaker, right speaker, or somewhere in between. This control is called panning, and there are two main ways to control this in Studio One.

The first is to statically set the panning value for a track. To do this, click the “Mix” button in the bottom right to open the mix window. This window is used for managing various plugins, audio routing, and balances in a project. (full tour later) Underneath the small windows showing the track’s audio source and destination routing is a blue bar. This bar is what controls the panning. Dragging this to the left will make the sound come from the left audio channel and vise versa. You can set this specifically by double clicking on the number beneath this bar and entering the desired pan value. Now, all audio on this track will follow the panning set here.

But what if you want to have the panning change during the source of the project? To do that we need to look at the automation. To open this, select the automation button in the top-left section of the screen, and select the dropdown menu (defaults to “Display: Off”) and select panning. If you do not see panning as an option, see the lesson on automation for further steps.

The bar that appears on the track represents the panning over the course of the project. Double click to add a point to the line. These points can then be moved to set a specific value at a specific time. Up pans left and down pans right. Utilizing this method of panning can allow you to move a sound source around while it is playing, which can add a lot of texture to your project without having to alter the sound content itself.

To hide the automation, click the automation button again.

## Crossfades

Crossfades are an indispensable tool for working in any DAW. These occur when one audio event fades out while the next one fades in. You can manually create a crossfade by editing the event’s envelope flags, but there is a quicker way.

First, you need to have two audio events placed next to each other. Then select BOTH events and press the X key. You should see new flags appear on both events. You can then drag out the crossfades to the exact duration and speeds desired just like working with the envelope flags.

Crossfades are useful for combining audio because it can be extremely noticeable when two clips play back to back. This is due to both the audible silence between the clips, as well as a low-level click that can occur when moving from the silence to the second clip. To avoid this, add a crossfade whenever you have two audio clips playing back-to-back. 

## Reversing Audio

One commonly used effect is reversing an audio file. This will cause the computer to read through the file from end-to-start instead of start-to-end. You can hear this in several songs as a unique texture.

To reverse an audio event in Studio One 6 is quick and easy. Select the audio event you wish to reverse, and then right click. Under Audio Options or the Action menu, you will see the option to reverse the audio. This can also be done with CTRL/CMD + R on the keyboard. Once reversed you will see the waveform update accordingly in the main Studio One window.

Here is a video briefly showing what reversing audio can sound like using a sample from former US president Barack Obama.

!?[obama-backward-yes-we-can](https://www.youtube.com/watch?v=Ewo20rq2Qbw)

## All About Automation

When creating a mix, generally you will have two different kinds of parameter settings: those that stay the same, and those that change over the course of the song. This page will be focusing on the latter. Let’s say you wanted to have the audio of a track automatically get louder during a chorus section, or have the guitar change which of the stereo speakers it is heard from each time a phrase repeats. How would you do this? The Answer is automation!

To open automation, there are a few options, but the easiest is to hit the Show Automation button or press the A key. This will toggle the automation visibility for all of your tracks. You can easily hide this by pressing the buttons again. Don't worry, this will not get rid of any automation you set. By default, no automation is selected, but you can select from a list of options with the dropdown menu that appears by each track in this mode. By default, it will say Display: Off.

Audio tracks will automatically have three options in this menu to choose from. These are:

* Volume: The level, in dB, of the track at that given time
* Mute: Completely silence a track for a duration of time
* Pan: The balance of the track between the left and right output speakers when played back.

Instrument tracks do not have anything loaded into them by default because the potential options can change based on the instrument loaded into the track. However, you can easily add the above options by following these steps:

1. Have an instrument on the track.
2. In the dropdown menu, select Add/Remove.
3. In the Automation window popup, you will see everything that can be automated for that specific track. Open the Audio folder.
4. Double click on Volume, Mute, and Pan L/R to add them to the list on the list side of the window. (or select and use Add and Remove buttons)

The elements on the left side of the window are what will appear in the automation dropdown. You can customize this for each track. The parameter options will change based on the total number of options available. For example if you add a reverb to a track, you will see a folder called Inserts. Inside of there you will see each effect as a sub folder that contains the automatable parameters. So if you wanted to change the decay time for that reverb you would first add the effect, then navigate to the folder and add the desired parameter to the automation list.

Once you know which parameter you wish to automate, select it from the drop down menu. The contents of the track will be blacked out and a line will appear. Each parameter has a unique line color to help differentiate them. The line represents the parameter volume at that point in time. Double click on the line to add an automation point. You can then click and drag the automation point to the desired time and level. (The bottom of the track is the parameter minimum and the top is the parameter maximum). You can add as many points as you need.

To change the curve of the automation points, click on the dot that appears on the line segment between two automation points. You can change how logarithmic or exponential the curve between the points are.

This video shows the automatic value changes will happen as a song plays by automating the volume on 8 different tracks. The device in question is the [Presonus Faderport 8](https://www.sweetwater.com/store/detail/FaderPort8--presonus-faderport-8-production-controller) which automatically adjusts its faders to volume automation parameters.

!?[automatic-faders](https://www.youtube.com/shorts/NrtX-SxtCP0)

When playing back the audio, you can have the automation behave in different ways:

* Read: Performs the automation as given.
* Touch: Will only update the automation when an external MIDI controller is used. When a MIDI controller is not being actively updated, it behaves like Read.
* Latch: Reads the automation until a hardware input is detected, then begins writing the automation data from that point onward.
* Write: Will only write automation data. Be careful that if you set the automation, then playback while still in Write mode, it will overwrite the previous automation!
* Off: Ignores all automation when playing back. This will translate to the mixdown, so don’t forget about it!

## Lab 6

Lab Objectives:

* Crossfades
* Introduction to the Mixer/Console
* Volume and Pan Automation

Instructions:

1. Create a duplicate of your project from Lab Assignment 2. Rename the new copy “YourFirstNameYourLastName-Lab6”.
2. Download a few interesting audio files from Freesound.org and/or the University of Iowa Musical Instrument Samples repository. The content of the files is at your discretion, but they must be in an uncompressed format - this includes wav, aiff, Apple Lossless, FLAC or caf files. Mp3 or AAC are prohibited.
3. Drag-and-Drop these new files onto new tracks in your Lab Assignment 3 project.
4. For the remainder of the lab time, experiment with the three techniques listed in this assignment’s objectives. Your final submission at the end of the lab must include one example of each:
    * Crossfades
    * Using the Console to set static volume and pan values
    * Volume and/or Pan Automation: Look for intriguing ways to combine the sounds that you have collected so far - perhaps two audio files complement each other when their volumes are balanced a particular way, or a sound that sweeps across from the left to the right using pan automation is a dramatic introduction to a contrasting sound.
5. When you are finished, export the audio as instructed in “Mixdown Requirements” and submit it to your teacher.
As always, save a backup copy on your personal storage media. This can be a flash drive, SD card, or online cloud storage. Be sure to backup both the session AND the exported audio.


Mixdown requirements:

* File name: YourFirstNameYourLastName-Lab6.
* Format: Wave or MP3 at 44.1kHz sampling rate and 16-bit resolution (128 kbps for MP3 files). Just one, you don’t need to mixdown two files.
* Do not adjust loudness.
* Make sure to export the Main output.
* Be sure that the duration of the resulting audio file matches what you expect. Your Lab project should be between approximately 45 and 120 seconds in duration.
* Be sure to follow your teacher’s guidelines for file submission.
