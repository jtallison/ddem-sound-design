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

When playing back the audio, you can have the automation behave in different ways:

* Read: performs the automation as given.
* Touch: will only update the automation when an external MIDI controller is used. When a MIDI controller is not being actively updated, it behaves like Read.
* Latch: reads the automation until a hardware input is detected, then begins writing the automation data from that point onward
* Write: will only write automation data. Be careful that if you set the automation, then playback while still in Write mode, it will overwrite the previous automation!
* Off: Ignores all automation when playing back. This will translate to the mixdown, so don’t forget about it!
