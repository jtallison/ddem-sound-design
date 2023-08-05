# Unit 5: All About MIDI

Unit 5 introduces the concept of MIDI and MIDI controllers. Once you've added a device to Studio One we will go over the various software instruments included in Studio One 6 and how you can record MIDI data to have those instruments perform automatically. AFter going over a few techniques for imporving the MIDI recordings we will have a few lab projects that will further explore the synthesizers and performing your own music.

 

## What is MIDI

MIDI is a protocol for sending instructions from one musical instrument to another. First released in 1982, MIDI stands for Musical Instrument Digital Interface, and allows for instruments (and other digital devices) to send control messages to other instruments. Early on this was largely used to allow for keyboard control to various synthesizers, allowing a single person to control multiple instruments with a single keyboard.

MIDI signals are usually sent through a 5-pin MIDI connector, and generally have two main components for each message. The first component is a label that tells the receiving device how to utilize the numeric value which follows. The numeric values range from 0-127, so a message to play a note would look something like this:
noteOn 60;
Here, the controller is telling whichever connected device to begin playing MIDI note 60 (middle C). When it is time to stop playing a separate noteOff will be sent. Different messages and channels allow for a large variety of devices to be chained together and controlled all from a single controller!

MIDI is also useful for controlling hardware that is capable of saving multiple timbres. Some synthesizers will have presets for piano, brass, and other kinds of sounds, Using pre-written MIDI files, instructions for these devices to play back full musical compositions became possible. As this feature became more common, General MIDI was developed as a uniform way of organizing the various potential timbres and sounds. Any device that is General MIDI compliant will respond to a MIDI file in the same way. Otherwise, one device may take a message and begin playing the drums while another would begin playing the trumpet.

As computers became more powerful it became possible to send MIDI messages over a USB connection. 5-pin adapters exist for older controllers, but most modern controllers will have a dedicated USB port to interface with a computer. Generally speaking, this connection is used in order to control the software instruments on the computer. By opening a DAW, the user is able to record and play back the notes for that software instrument. There are other potential uses as well, but we will be focusing on recording MIDI note entry in this course.

When it comes to modern MIDI controllers there is a lot of variety in terms of features and form factor. Many controllers utilize a piano keyboard interface, but as long as the device can send MIDI messages on command, the physical design can be as varied as the designer wants. A few common designs are:

* Keyboard
* Sliders
* Buttons
* Drum pads

Some of these controllers may only be a piano keyboard, or a bank of buttons/pads while others may mimic an audio mixer or be completely customizable. Partly because they offer the largest variety of control options in a single unit, one of the most common MIDI controller layouts will utilize a piano keyboard along with a few buttons, sliders, drum pads, and/or switches. The specific price point of these controllers will vary based on multiple factors such as the number of keys and extra features, but many are currently around the $100 USD price point at the time of writing this page.

## Test Your Knowledge!

What does MIDI stand for?

- [[ ]] Momentary Input, Delayed Intersampling
- [[ ]] Musical Interface for Digital Instruments
- [[ ]] Michigan Developed Interplay
- [[X]] Musical Instrument Digital Interface
- [[ ]] It doesn't stand for anything.

## Connecting and Mapping MIDI controllers to Studio One 6

There are multiple ways to input data into Studio One. The most direct way is to individually click and enter every single note and parameter. This will give you the greatest level of control, but is extremely time consuming and not very musical. To help with this, you can utilize a MIDI controller. Before we discuss common features of MIDI controllers and a few recommended options, it is important to state that none of the companies have sponsored this page in any way,

Because a MIDI controller is mainly just sending MIDI control messages to the computer over a USB connection, there have been a large number of MIDI devices created over the years. The most common ones are shaped like a standard piano keyboard, but there are others that mimic mixers, drums, are only banks of buttons, or function like wind instruments, just to name a few. Each person will have their own needs and preferences when getting a MIDI controller, but if you are getting one yourself and aren’t sure what to look for, most all-purpose controllers have variations on the same four features:

* Piano keys for entering notes. This will usually be the main section of the controller
* Buttons. These can vary, but many are programmable to do whichever you need in your DAW.
    * Some controllers, especially those designed to work with a specific DAW will have buttons dedicated to controlling playback and recording as well. Usually these cannot be easily remapped.
* Knobs/Sliders. Are useful for controlling things such as a channel’s gain fader, automation, and anything else that needs more control than a simple button
* Drum pads. These are special buttons that function like the keyboard, but with a percussive feel to them. They are usually pressure sensitive, and can be used to easily trigger drum samples in a mix.

If you are wanting to get a controller, I recommend finding one with a mix of these features unless you specially need something specific. A few general options are:

* [Akai MPK Mini Mk III](https://www.sweetwater.com/store/detail/MPKMini3--akai-professional-mpk-mini-iii-25-key-keyboard-controller) 
* [Arturia MiniLab 3](https://www.sweetwater.com/store/detail/MiniLabMk3--arturia-minilab-3-25-slim-key-controller) 
* [Novation Launchkey Mini MK3](https://www.sweetwater.com/store/detail/LaunchK3mini--novation-launchkey-mini-mk3-keyboard-controller) 
* [M-Audio Oxygen Pro Mini 32](https://www.sweetwater.com/store/detail/OxygenPMini--m-audio-oxygen-pro-mini-32-mini-key-keyboard-controller)
* [PreSonus ATOM SQ](https://www.sweetwater.com/store/detail/ATOM-SQ--presonus-atom-sq-keyboard-pad-hybrid-midi-keyboard-pad-performance-and-production-controller)

With the exception of the ATOM SQ, these controllers are generally around the $100 USD price point. Generally the price will increase as the number of keyboard keys and other features increase as well. The ATOM SQ is designed to work directly with Studio One and both automatically update to the state of Studio One 6 and has playback controls built into it. Because it can also be used with other programs such as Ableton Live, it is generally worth the $250 USD price point if you can afford it. Another unique aspect of this controller is that the keyboard is made entirely out of drum pads allowing for more flexibility.

Once you have your controller, be sure to connect it to your computer and install/update any drivers per the instructions of the controller. Once connected and powered on you can open Studio One 6 and from the main window select “Configure External Devices” in the bottom of the middle panel. (this may be hidden depending on your monitor resolution, but you can get to the same window by clicking on “Configure Audio Devices” then “External Devices”.) Here you will see a list of the MIDI devices that Studio One has saved and is expecting to be connected. To add a new device, click on “Add”.

In the window that pops up you will see a large number of brands in a list on the left. If your device already has a template within Studio One, you can find it on the list and select it to save a few steps. If you do not see it here or want to manually set up your controller, continue here. Select “New Keyboard” from the list and in the panel to the right, begin entering information. You can type whatever you want for the manufacturer and keyboard name, but I recommend keeping it accurate to the device so that you can easily identify the keyboard in the future, especially if you have multiple MIDI keyboards.

Next, click the drop down menu labeled “Receive From” to see a list of all connected MIDI controllers and select your device. If you do not see it here, then you may need to reconnect the device, install/update a driver, or restart Studio One. This will tell the computer which connected device to look at and receive MIDI messages from. You can filter only specific kinds of messages if desired as well. You do not need to set anything for the “Send To” option unless you are connecting a hardware instrument to your controller via a MIDI cable. This option is for sending MIDI messages from Studio One to external hardware.

Once you have selected your sedated settings, click on “OK” to add the device. To test the new controller you can open a new session and create a new instrument track. The specific instrument doesn’t matter, but Mai Tai will work well for testing multiple notes at once. When the device is connected and working you should see an orange bar appear next to the track whenever you press a key on the keyboard. (and hear a sound if there is an instrument attached) 

Lastly, to program any customizable knobs, buttons, or sliders on your controller it is very simple. First, notice the top-left of the screen. Here you will see a window containing the last control input from the MIDI controller as well as the last parameter you interacted with in Studio One. Simply adjust the desired parameter, then adjust the button/key/slider/knob you wish to map it to. When both of the elements in the boxes are correct, click on the arrow in between the two elements to map it. Now, whenever you use that specific control on the MIDI controller, the mapped parameter will automatically adjust itself. This is super useful for controlling parameters such as volume and panning quickly and easily no matter which screen you are looking at in Studio One.

A video breakdown of the above steps can be found here: 

!?[midi-controller-video](https://www.youtube.com/watch?v=Wc-SOxMVIkU) !?[midi-mapping-video](https://www.youtube.com/watch?v=WJ_5uJb3alc)

For more information about connecting MIDI controllers to your device, check out the [Studio One 6 online manual](https://s1manual.presonus.com/StudioOneReferenceManual.htm#Setup_Topics/Set_Up_Your_MIDI_Devices.htm?TocPath=Setup%257C_____4).

## Software Instruments

Before you can hear any MIDI notes play in Studio One 6, you need to have an instrument set to play them. Start by making a new instrument track with the T key shortcut. You can select an instrument directly from this window if you know what you want, but let’s leave it as empty for now. Once you have your track made, open up the browser window and navigate to the instruments section.

This is where all software synthesizers that Studio One 6 can utilize are located. If you have other instrument plugins installed on your device, you will see them here alongside the ones included with Studio One 6. To help differentiate these, you can sort them by vendor. Here we will only be discussing the instruments that come with Studio One 6. To open the synthesizer, simply click and drag it from the browse window onto the track you just made. The synthesizer interface will open automatically. If you drag to the area below your last track, then Studio One will make a new track with the instrument on it. If you close the interface window and need to open it again, simply click on the small keyboard icon on the track.

Check out the [Studio One 6 online manual](https://s1manual.presonus.com/StudioOneReferenceManual.htm#The_Browser_Topics/Instruments_and_Effects_Tabs.htm?TocPath=The%2520Browser%257C_____4) for more information on the Instruments tab.

Impact XT:
This is the drum machine instrument in Studio One 6. Depending on your storage space, you may have more or less kits installed, but using the drop down menu, you can select from a variety of drum samples to build a custom drum machine. Impact has eight banks of 16 slots, allowing for a total of 128 different samples per instance of Impact. If you want, you can also drag and drop other audio files into Impact; these can be anything, not just drums! Once a file has been loaded into impact, there are a variety of settings and alterations you can make inorder to have Studio One playback the audio just how you want it. From there, while recording, you can trigger the sound either with a MIDI controller or by clicking on the virtual drum pads to trigger the audio file. The MIDI note for each pad is given in the corner.

You need to load samples either manually or via a preset in order to hear anything in Impact. There are no sounds loaded by default.

Mai Tai:
Mai Tai is a polyphonic synth that is generally used for a variety of purposes in Studio One. You can utilize this for chords, leads, basslines, and just about anything else. Mai Tai has two main oscillators, filters, amplitude envelopes, and a few built in effects. One thing to note however, is that this will sound distinctly like a synthesizer. It is NOT used to model real-world instruments.

Mojito: 
By comparison, Mojito looks much smaller than the other synthesizers. Its interface only has a few knobs on it. Timbrally, Mojito is fairly similar to Mai Tai, but there is one important distinction. Whereas Mai Tai can play multiple notes at one time, Mojito is monophonic. This means that it can only play one note at a time. If you were to try and play a chord, then either multiple notes will be ignored, or Mojito will play one then slide to the next note. Because of the monophony, Mojito is generally used for basslines or melodic content; basically everything that isn’t a chord. By comparison, it has a simple single oscillator, a filter, envelope, and a few effects.

Presence XT:
Presence is mainly used to replicate real-world instruments within Studio One 6. This is useful for including instruments in your project that you may not have access to record. Once you have selected an instrument from the presets, you can then utilize the interface, which is almost identical to the Mai Tai interface to tweak exactly how the instruments sound. One important thing to note however are the red keys on the left side of the piano roll that will change for each preset. These do not play a note, but rather change the loaded program for that instrument. For example, a string instrument would play normally, but you could swap to a tremolo, a crescendo, harmonics, or several other playing techniques by hitting that specific MIDI note. The MIDI notes that create pitches for a given preset are indicated with a white bar above the notes.

You must select a base program for Presence to make sounds. It will not work without a base programmed instrument to model.

SampleOne:
SampleOne is similar to Impact in the way that you need to load sounds into the instrument in order for it to begin making audio. However instead of loading multiple samples and playing back different ones, SampleOne will load a single sample and then transpose it along the keyboard. This can allow you to use a single sample at a variety of pitches or as a chord quickly and easily. You can either drag and drop a pre-recorded sample into SampleOne, or record directly into the instrument. From there you can edit the audio in many of the same ways as you could in Impact. One important thing to note is that the transposition occurs by changing the playback speed of the sample, so higher pitches will play quicker than lower pitches.

You need to load or record samples in order to hear anything in SampleOne. There are no sounds loaded by default.

Check out the [Studio One 6 online manual](https://s1manual.presonus.com/StudioOneReferenceManual.htm#Built-In_Instruments_Topics/Chapter-Built_in_Virtual_Instruments.htm?TocPath=Built-in%2520Virtual%2520Instruments%257C_____0) for more information on each of the instruments included in Studio One 6.

## Metronome

When recording anything, it is helpful to have a metronome to keep time. This will allow the performer to stay in sync with other performers or any pre-recorded tracks. You can see the metronome in the bottom right of the screen. It is the right-most section of the transport bar. 

To set the tempo for the metronome, you can double click on the number above the word Tempo, and then enter the desired beats-per-minute (BPM) of your song. If you don’t know the exact BPM, then you can keep clicking at the desired tempo in order to set the tempo to match the rate of your clicking.

You can adjust the time signature as needed with the Timing section. The default is 4/4, but you can adjust this to match the music you are recording. This is useful because it will change the grid to match when the timebase is set to Bars, allowing for easier lining up of content, as well as changing the metronome sounds to clearly mark each measure.

To hear the metronome, there are three different setting windows we can access above the Metronome sections. The icon that looks like an analog metronome (the triangle and stick) turns the metronome on and off. You can also trigger this with the C key. The circle icon indicates the precount. When this is on the metronome will click for a certain amount of time BEFORE the recording starts. This is useful for letting the performer feel the tempo before they need to begin playing, and is recommended whenever recording. If you want the performer to hear other things, you can turn on pre-roll, which will behave the same, except instead of clicking the metronome, will playback the session contents before recording begins.

In order to change how long the precount is, load presets, or change the metronome sound you can click on the wrench icon to open the metronome settings. One useful tool is the render button. This will take the metronome settings you have and render the metronome as an audio track. This is useful for saving on CPU performance, but if any timing elements of your project change, you will have to update the rendered track.

For mroem information on the Studio One 6 metronome controls, check out the [Studio One online manual](https://s1manual.presonus.com/StudioOneReferenceManual.htm#Recording_Topics/Metronome_Control.htm?TocPath=Recording%257C_____4).

## MIDI Quantization

When recording MIDI it is extremely likely that some of your notes will be slightly off of the metronome. This is due to both human error in performing as well as latency between the various devices. In some instances the difference may not be enough to notice or may be a desired effect. When working with your MIDI recordings you can utilize the quantize tool in order to quickly and easily set your MIDI information to the desired metric placement. 
When the computer quantizes a MIDI note it looks at the beginning of the note and then changes the starting position to the closest metric division. This can be both extremely useful and extremely frustrating at the same time. This is useful for lining up material, but frustrating because the computer does NOT analyze if something is intended to be on a specific beat; it just moves the note to the closest option. When quantizing, ALWAYS be sure to double check what has happened and make any adjustments as necessary. Errors can be mitigated with proper settings, but it is good practice to double check.
To quantize, first select the MIDI event you wish to work with and open the EDIT window. Select the notes you wish to quantize and then click the Q button to open the Quantize menu. Here you can set various settings such as the metric division for the quantization, swing,  velocities, and patterns. The specific division will depend on the content, but the 8th or 16th note divisions are generally a good place to start. You can set the quantization to follow a specific groove, but that is beyond the scope of this course. What is extremely useful for this course however is the ability to save quantization presets. By default 5 exist with different metric divisions, but if you will be having multiple different quantization settings, saving them and easily swapping between them is a major time saver. When you have set your various settings, click Apply to execute the quantization. 
In order to quantize effectively, there are a few techniques and tools that can help you, and offer different results rather than just hoping your settings are right and relying on the computer.

For mor einformation on MIDI quantizing, you can check out this page in the [Studio One 6 online manual](https://s1manual.presonus.com/#Editing_Topics/The_Grid.htm?TocPath=Editing%257C_____4.

* Swing: The swing parameter will shift notes on the upbeats away from the grid. Higher percentages will result in more dramatic shifts, though sometimes a subtle use of the swing parameter can be very effective.
* Humanize: Humanize is available from the Action menu in the Piano Roll Editor. Running the Humanize action while notes are selected will randomly shift their timing slightly off the grid, making the performance a little less perfect but potentially more “natural”.
* Manual Adjustment: Holding Shift while dragging notes will prevent them from snapping to the grid. You can use this technique to make individual notes happen just a little early or late (a technique often used in hip hop and neo soul drum programming). This can be especially effective on snare drums or claps.
* Miscellaneous: Look at some of the other actions in the Action menu – “Length” and “Velocity” are particularly helpful. They can help to make the lengths and velocities of MIDI notes that you recorded more even and regular if desired.

## Test Your Knowledge!

Which of the following kinds of devices can be used to record MIDI data onto an instrument track in Studio One 6?

- [[ ]] Audio Cables
- [[ ]] Microphone
- [[X]] MIDI controller
- [[ ]] Monitor Speakers
- [[ ]] Analog Mixer

## Lab 3

Objectives:

* Basic MIDI recording and quantizing
* Working with Virtual Instrument presets
* Implementing Audio Loops

Instructions:

1. Open your DAW, create a new song/project with the title “YourFirstNameYourLastName-Lab5”. If prompted, use the following settings:
    * Sample Rate - 44.1kHz
    * Resolution - 16 bit
    * Tempo - will be changed later
2. Open the Loops tab of the Browser panel on the right side of the window. Find a drum loop that you like and change your song tempo to match the tempo of the loop - the selected loop’s tempo is listed at the bottom of the loop tab. Drag your loop onto a new track in the Arrange window.
3. Open the Instruments tab of the Browser panel. Drag an instance of the Mojito instrument onto a new track in the Arrange window. Ensure that your MIDI keyboard is working - press a few keys and you should hear a sound. If you do not, see me to make sure that your MIDI keyboard is set up correctly. Choose a bass preset sound from the preset dropdown menu in the software instrument’s window.
3. Play along with your drum loop a few times to come up with a bass line. Once you have something you want to record, turn your attention to the Metronome. Set a Metronome Precount for 2 bars - this means that when you hit record, you will hear 2 bars of clicks (8 beats) before the recording actually starts.
4. Record!
    * Arm the record enable button by the track name of your Mojito track. This will not be visible if you have automation showing.
    * Skip the playhead to the beginning of your song.
    * Click the record button in the transport bar. You should start hearing the metronome counting down - remember, it will give you 2 full measures (8 clicks) before it actually starts recording.
    * Play along with the drum loop like before - you’re now recording MIDI.
5 .You probably didn’t play the part perfectly. Double-click on the newly recorded MIDI region to open the piano roll editor at the bottom of the screen. Snap the notes onto The Grid using an operation called “Quantization”. Make sure that “Auto Quantization” is turned on via the AQ button. Select all of the MIDI notes in the piano roll with [Ctrl+A] on Windows or [Command+A] on Mac and select a value from the quantize dropdown menu. You might have to try a couple of different values - start with 1⁄8 and listen to see if that worked. If it did, your bass part should be perfectly in time with the drum loop. If it didn’t, try 1⁄4 or 1⁄16.
6. When you are finished, export the audio as instructed in “Mixdown Requirements” and submit it to your teacher.
7. As always, save a backup copy on your personal storage media. This can be a flash drive, SD card, or online cloud storage. Be sure to backup both the session AND the exported audio.

Mixdown requirements:

* File name: YourFirstNameYourLastName-Lab3.
* Format: Wave or MP3 at 44.1kHz sampling rate and 16-bit resolution (128 kbps for MP3 files). Just one, you don’t need to mixdown two files.
* Do not adjust loudness.
* Make sure to export the Main output.
* Be sure that the duration of the resulting audio file matches what you expect. Your Lab project should be between approximately 4-8 bars in duration.
* Be sure to follow your teacher’s guidelines for file submission.

## Duplicating Events

Let’s look at this screenshot of a Studio One session. In it there is a MIDI drum part made with Impact, as well as an audio recording of a guitar chord progression. Notice how the chord progression is longer than the drum loop? In order to have the drum loop repeat itself we can simply duplicate it. Duplicating will work for both audio and MIDI events, and will repeat the selected material; this makes it much quicker than copy and pasting!

To duplicate something, select the region you want to duplicate and then press the D key on your keyboard. Pressing D multiple times will make multiple duplications. All duplications are placed immediately after the original event, and can be moved as desired.

## Event Options

When working in Studio One you can generally edit sounds in two main ways: changing the content of the original file and using effects to change how the file is read by the computer. Here we will be focusing on the first of those options. 

When in the main workflow of Studio One, you can right click on an event and see a variety of options. At the bottom of the menu will be three categories: Event, Audio, and Instrument Parts. Musical Functions will appear instead of Audio when selecting an instrument track, but there will always be three options. Hovering over the category will bring up a sub-menu with the various options available. If an option is not selectable, then you are unable to perform that action. Generally this can be remedied by selecting the specific elements you need to apply that action to.

Event: These are general actions that can be applied to anyevent in Studio One. These include items such as moving events, muting, combining, cropping, and rendering the event.
Audio: These are actions that will directly alter the audio present in an event. Audio Event actions include creating crossfades, detecting chords, normalizing audio, reversing audio, and stripping silence.
Instrument Parts: Lets you create new instrument parts and note patterns, render detected chords, and more
Musical Functions are applied to MIDI notes and are used for creating musical content from the notes. These functions include transposing, extending, and repeating notes, combining events, fitting notes to scales, etc.

When working in the Edit Window, you can also access the relevant options through the Action menu.

## Lab 4

Objectives:

* MIDI quantization editing
* Swing
* Humanize
* Manual adjustment
* Synth parameter automation


Instructions:

1. Open your DAW, create a new song/project with the title “YourFirstNameYourLastName-Lab7”. If prompted, use the following settings:
    * Sample Rate - 44.1kHz
    * Resolution - 16 bit
    * Tempo - your choice (try to get away from 120)
2. Open the Instruments tab of the Browser panel. Drag an instance of the Impact sampler instrument onto a new track in the Arrange window.
3. Load a preset in Impact and adjust settings as desired. Record a four bar drum part. Remember to utilize the metronome and precount from Lab 5 as needed while you write and record your part.
4. After your drum part has been recorded, open the piano roll editor and quantize. Then, explore some of the additional quantization and MIDI editing techniques such as swing and humanize.
5. When you are finished editing the drum part, drag an instance of Mojito or Mai Tai onto a new track in the Arrange window. Adjust settings as desired and record a part to accompany your drum part.
6. After your synth part has been recorded, open the piano roll editor and quantize. Then, explore some of the synth parameter automation other than volume, panning, and mute. You may want to manually test some synth parameters before deciding which ones you want to automate.
7. Before submitting your assignment, ensure that your song includes:
    * A drum part using the Impact instrument that has been “creatively” quantized (meaning that there is some application of swing, humanization, or manual shifting of notes after the initial quantization)
    * Two instances of Mojito or Mai Tai synth parameter automation that are NOT volume or pan – these can be on the same track or two different tracks if you decide to record a second synth part.
8. When you are finished, export the audio as instructed in “Mixdown Requirements” and submit both to your teacher.
9. As always, save a backup copy on your personal storage media. This can be a flash drive, SD card, or online cloud storage. Be sure to backup both the session AND the exported audio.


Mixdown Requirements:

* File name: YourFirstNameYourLastName-Lab4.
* Format: Wave or MP3 at 44.1kHz sampling rate and 16-bit resolution (128 kbps for MP3 files). Just one, you don’t need to mixdown two files.
* Do not adjust loudness.
* Make sure to export the Main output.
* Be sure that the duration of the resulting audio file matches what you expect. Your Lab project should be approximately 8 bars in duration.
* Be sure to follow your teacher’s guidelines for file submission.


## Lab 5

Objectives:
* Exploring Mojito and Mai Tai virtual instruments.

Instructions:

1. Open your DAW, create a new song/project with the title “YourFirstNameYourLastName-Lab6”. If prompted, use the following settings:
    * Sample Rate - 44.1kHz
    * Resolution - 16 bit
2. Open the Studio One Reference Manual under the Help menu. Navigate to Built-In Virtual Instruments and read the entry for Mojito.
3. Open the Instruments tab of the Browser panel. Drag an instance of the Mojito instrument onto a new track in the Arrange window.
4. Do not load a preset. Instead, explore only the oscillator (OSC), amplifier (AMP), and filter (FLT) sections of Mojito. Make some changes until you like what you hear.
5. Open a text editor of your choice (TextEdit, Microsoft Word, Google Doc, etc.) and, in one or two sentences, describe one of the changes that you made - what parameter did you adjust, what was the effect on the sound, and why did you like it better after the adjustment?
6. Record a few MIDI notes using this new sound. You do not need to worry about setting up your metronome or composing a melody - this is just to serve as a quick reference for your instrument settings.
7. Repeat steps 3-6 with a second instance of Mojito on a new track. Make sure that it is clear in your writeup which instance you are referring to when writing your description.
8. Repeat steps 2-6 with one instance of Mai Tai. In Mai Tai, explore both oscillators (Osc 1, Osc 2), the filter (Filter), and the amplifier (Amp Env). You may also incorporate the Noise section if you wish, but ignore all other sections for now.
9. Save your writeup text file and be sure to include it along with your audio submission. When you are finished, export the audio as instructed in “Mixdown Requirements” and submit both to your teacher.
10. As always, save a backup copy on your personal storage media. This can be a flash drive, SD card, or online cloud storage. Be sure to backup both the session AND the exported audio.

Mixdown requirements:

* File name: YourFirstNameYourLastName-Lab5.
* Format: Wave or MP3 at 44.1kHz sampling rate and 16-bit resolution (128 kbps for MP3 files). Just one, you don’t need to mixdown two files.
* Do not adjust loudness.
* Make sure to export the Main output.
* Be sure that the duration of the resulting audio file matches what you expect. Your Lab project should have each synthesizer play one after another, with no more than 2 seconds of silence between them. The full recording should be under 48 seconds.
* Be sure to follow your teacher’s guidelines for file submission. DO NOT FORGET THE TEXT WRITE-UP PORTION OF THIS LAB!!

 