# Unit 4: Recording and Editing Audio

Unit 4 goes over everything you need to know to start making your own audio recordings using Studio One 6. We will start with a discussion on how a microphone works and how to position them to get clear recordings, and the computer settings to make sure everything comes through as expected. Then we will go over a few things you can do within Studio One to improve the quality of your recordings to use both in the Lab project and any future projects. 

<section>

## Microhones and Speakers: How Do They Work?

Microphones work as electronic ears. Using electricity, they receive an incoming sound wave and convert it to electricity, then send that electricity off somewhere else to be used or recorded via wires. This process is extremely similar to the human ear converting sound waves into nerve impulses and sending those to the brain. There are many different microphones, but they can generally be broken into three main categories. Each of these categories of microphones go about doing the same thing in slightly different ways. This list is not exhaustive, but will cover the main types of microphones you will run into when recording.

Dynamic microphones are handy for several reasons. Generally speaking, dynamic microphones are sturdy. They can handle louder volume levels and physical abuse better than other kinds of microphones. Generally, they are seen a lot in live music performances and for recording louder sounds like drums.

A dynamic microphone works by having a diaphragm that incoming sound waves hit. The pressure causes the diaphragm to move back and forth. This movement is a VERY small amount, but enough for the microphone to work. Connected to the diaphragm is a wire which is coiled around a magnet. This movement causes a small amount of electrical current to be created. This current is analogous to the air pressure, and sent through the wires from the microphone to be recorded or amplified. Because of how they work, generally a dynamic microphone needs to be close to the sound source in order to pick it up accurately.

Condenser microphones tend to be more delicate than dynamic microphones, and can generally be found in a studio recording setting. There are two different sub-categories of condenser microphones, but they both function in the same way. A diaphragm picks up incoming sound waves, which moves the diaphragm. However unlike a dynamic microphone, in a condenser there is a second metal plate with an electric current flowing through it. Simplifying the internal circuit, as the two diaphragms move closer and farther from each other the resulting electric current will change so that it is analogous to the incoming sound wave, which is then sent off to be used elsewhere. The main difference between the two subtypes is the size of these diaphragms. Small-diaphragm condensers are useful for getting accurate recordings, whereas large diagrams are usually used for adding a unique color to the recorded sound. Condenser microphones require an additional 48 volts of phantom power in order to function, but can generally be placed farther away from the source than a dynamic microphone.

Ribbon microphones are the third main category of microphones. They function by having an extremely thin metallic ribbon suspended in a magnetic field. Similar to the cochlea, different frequencies will stimulate different portions of the ribbon. The vibrating strip will then generate an electric signal to be used elsewhere. Historically these microphones are extremely delicate. Excessive electric current could burn out and destroy the ribbon. Modern ribbon microphones are more resilient, and a few require phantom power in order to work, but they are still fairly delicate. Ribbon microphones can offer a unique color and warmth to a sound that other microphone types do not have. Generally, they have been used on voices and when recording electric guitar amplifiers.

All microphones have a polar pattern. That is a specific area that they are designed to pick up sound from. Most microphones will be a cardioid pattern, which has a dedicated “hot” end, and another end that rejects any sounds. When drawn in two dimensions, this pattern looks similar to a heart. 

A few other common patterns are:

* Hypercardioid
* Figure 8
* Omnidirectional

## Microphone Placement

## Clipping and How to Avoid it

When recording audio there is a limit as to how loud a sound source can b ein order to be accurately recorded and reproduced. If a sound source is recorded with too much gain, then it will be distorted. This happens because the ADC will be unable to properly convert the excessively large signal to a specific numeric value. All values that are too large will be recorded as the largest possible value possible by the ADC. Effectively clipping off part of the audio. This can be clearly seen when looking at the waveform for the audio file.

In addition to distortion, clipping can sound like clicks and pops as well. This is in part because of the extremely fast sampling rate. Unless a sound source is EXTREMELY loud and the recording is improperly set up, there will still be a large number of the original samples that will not be clipped. The result of this is generally being able to hear the original sound with the clipping mixed into it.

In general, the best way to avoid clipping is to make sure nothing is too loud. When mixing a red notification light will appear on the mixing console for the main output channel to indicate clipping. When mixing the audio care should be taken to make sure nothing is too loud. A simple fix is to lower the main output volume. Another option is to find the offending portion of audio and make it softer to remove the clipping. Depending on the context of the music however this may be difficult as it can alter the balance between the various sound sources. 

Another way to avoid clipping is with the use of a limiter. A limiter is an audio effect that will limit the dynamic range of a sound source, keeping it from becoming too loud. While quick and easy, this could reduce the total dynamic range of the track which may not be desired. To do this in Studio One, place a limiter effect on the post section of the main output. This is the final section before the audio is sent to the speakers, so it will encompass the whole mix equally. Set the preset to 0 dB and then the audio will never pass 0dB, and cannot clip.

## The Edit Window

When you double click on an even in Studio One, it will open the edit window on the bottom of the screen. (You can also open this by clicking the Edit button in the bottom right of the screen and selecting your desired event.) This window acts like a localized instance of Studio One where you can edit the fine details of an audio or MIDI recording. The specific layout of the Edit window will change depending on what kind of event you are editing.

Audio:
When editing audio you will see the waveform of your selected audio even in the Edit window. Keep in mind that this window is for directly editing the contents of the audio file, and not for processing the files through effects (like in the Mixing console). In this window we can see a mixture of new and familiar things. In general the toolbar that appears is identical to the one in the main Arrange window. Utilizing the tools here will only affect what is in the edit window, and not alter things globally. The new elements are:

Audio:

* Action Menu: This new button appears next to the macro toolbar button and will be the main one you utilize in this view. Clicking on this brings up a drop-down menu with a variety of actions you can do to your selected audio event. These include items such as normalizing, reversing, fade-ins, chord detection, etc.
    When right-clicking on an audio event in the main Arrange view, you can access this menu through the Audio sub-menu.
* The chords button appears next to the quantize menu and will allow you to detect chords present in the audio event and select those chords to apply actions to them.
* The last two buttons are used for visually arranging the Edit window. THe first button discussed here is next to the auto scroll button. This will sync the edit window with the Arrange window so that they are both visually lined up on the screen. Auto zoom is the final item on this toolbar and will automatically adjust the zoom to fit the entire event in the Edit window.

MIDI:

When editing a MIDI event, the view is very different. Instead of displaying the audio file, you can see the individual MIDI notes. This is the main way that you can adjust the MIDI content of a track. You can double click on the grid to add a MIDI note, then adjust the various values such as pitch and duration by moving the new note around on the grid.
* At the top right of the MIDI edit window are three viewing options. These change how the MIDI notes are displayed. The most common uses are the piano and drum views. The piano view will display all of the MIDI notes on a vertical piano roll, while the drum view will display only the beginning of each MIDI note in a grid layout. THe layout will automatically adjust depending on which instrument is on the selected track.
    The score view will display a musical score rendition of the MIDI notes. There are a handful of new options on the toolbar here. While this can be useful, it is not something covered in this course. If you would like more information on the Score View, check out that chapter in the [Online Studio One 6 manual](https://s1manual.presonus.com/#Score_Editor_Topics/Chapter-Score_Editor.htm?TocPath=Score%2520Editor%257C_____0).
* The action menu behaves the same as when editing audio, but will instead display actions relevant to working with MIDI. These include working with pitch, quantizing, filling notes, note velocity, etc.
* The next set of newly appearing buttons are all part of the quantizing toolbar.
    Note color will change the color of various elements of the MIDI notes.
    Select Automation by notes will allow you to select notes in th eMIDI roll, but instead of selecting the notes themselves, you can work with the automation tied to those notes.
    Auto-Quantize will quickly quantize the selected MIDI notes based on the quantization settings.
* Auto zoom appears here as well (in the same location) but the icon look different than in the Audio Editor.


There is no manual page specific to the edit window, but be sure to [check out this page on editing events](https://s1manual.presonus.com/#Editing_Topics/Edit_View_Event_Editing.htm?TocPath=Editing%257C_____16) (and the larger editing chapter in general) for more information on what you can do in the edit window.


## Timestreching

Timestreching is taking an audio file and slightly speeding it up or slowing it down in order to match the tempo of the Studio One session. Adjusting the speed of the file through timestreching will not alter the pitch of the original file. Excessively large stretches may still create noticeable pitch discrepancies, so it is best to utilize small amounts of stretching when needed. One example is a 4 bar drum loop recorded at 120 bpm being stretched to match a session tempo up to 20 bpm off from the original. This will allow the source loop to still be 4 bars long at a variety of tempi. You can set the timestreching manually or automatically.

To manually set the timestreching of an audio event, begin with the arrow tool. Float the mouse cursor to the left or right edge of the target Audio Event and hold Alt/Option on the keyboard. The Timestretch tool appears, and looks like an analog clock face. Then you can click on the edge of the Event and drag left or right to timestretch the Event, making it shorter or longer. In this case the length of the Event changes, using the Speedup factor, but the pitch of the audio remains the same. Only the Event that you selected for timestreching is affected.

Speedup factor is a timestreching function for making an audio clip shorter or longer while maintaining its pitch. This is used to stretch Audio Events when you do not wish to define a tempo for the original audio clip, which would affect all Events associated with that clip. The Speedup factor value changes during manual timestreching, and it also can be entered manually in the Event Inspector. Values greater than 1 decrease the length of the clip, while values less than 1 make the clip longer.

Note that manual timestreching can not be used on an Audio Event containing a sliced loop.

For automatic timestreching, you must open up the track inspector by selecting the desired track and pressing the F4 key on your keyboard. You can then select one of three timestreching option from the track inspector: 

Don’t Follow: Events on this Track are independent of the Song tempo. They are never moved or stretched automatically.
Follow: The start positions of Events on this Track are tied to the musical grid. Thus, the Events move when the Song tempo changes but they are not stretched.
Timestretch: Event start positions follow the Song tempo, as in Follow mode. In addition, the Events are stretched to fit the Song tempo.

You can also set the timestretch to one of four different modes depending on what kind of sounds you are working with and the desired effect. These modes are:
* Drums: Use this optimized mode on any percussion track to achieve the best results when stretching percussive audio. This mode uses the Elastique Direct algorithm.
* Sound: Use this general mode on any other type of track. This mode uses the Elastique Direct Formant algorithm.
* Solo: Use this optimized mode on any solo instrument or vocal track to achieve the best results. This mode uses the Elastique Pro Monophonic Formant algorithm.
* Tape: In this mode the track audio follows the song tempo by changing the sample playback rate. This results in the pitch moving up or down when the tempo changes, sort of like changing the speed control on a tape deck. Try this with drum loops or other samples when the pitch doesn't need to be exact.

For more information on timestreching, check out the [Studio One 6 online manual](https://s1manual.presonus.com/StudioOneReferenceManual.htm#Editing_Topics/Timestretching.htm?TocPath=Editing%257C_____10).

## Stripping Silence

When recording, especially when continuously recording through multiple takes, it is common to have sections of relative silence that you don’t need in the final mix. In Studio One you can easily program the DAW to look at your selected audio and automatically remove these unwanted sections of recording.

To strip the silence, you must first have an audio event with recorded audio already in it. You then select the events that you want to strip of their silence and click the Strip Silence button in the top toolbar. This opens a menu where you can customize the process. These options include how loud the silence threshold is, how long the silence is happening for, accounting for fades, and more. To apply the process, click the Apply button.

Here is a more detailed look at each of the settings present in the Strip Silence menu:

* Material: The first three options set the Open and Close Threshold for the gate algorithm automatically.
* Lots of Silence: Choose this for material that contains lots of silence and single hits—for instance, a clean, typical single-drum recording (hat, kick).
* Little Silence: Choose this for material that has some action going on but still has some silence—for instance, minimal techno/single drum loops, ride, or snare tracks.
* Noise Floor: Choose this for material where there is almost no real silence—for instance, noisy drum recordings, overheads, drum mixes, and drum loops.
* Manual: Allows the Open and Close Threshold to be manually edited.
* Open Threshold: Set between -80 and 0.00 dB.
* Threshold Link: Engage to link the Close Threshold to the Open Threshold.
* Close Threshold: Set between -80 and 0.00 dB.

Events This section determines the nature of the Events created after removing silence.

* Minimum Length: Determines the minimum length in seconds for any resulting Event.
* Pre-Roll: Determines the amount of time in seconds that should remain at the beginning of resulting Events from the time at which the previously detected silence ends.
* Post-Roll: Determines the amount of time in seconds that should remain at the end of resulting Events from the time at which newly detected silence begins.
* Fade-In: Determines the length in seconds of the linear fade-in applied to resulting Events.
* Fade-Out: Determines the length in seconds of the linear fade-out applied to resulting Events.
* Link: Enable this option to automatically set the Fade-In parameter to match the Pre-Roll setting, and the Fade-Out parameter to match the Post-Roll setting.

## Tuning and Transposition

Let’s pretend that you have a handful or recordings, but they are all in different keys. With Studio One you can easily transpose both audio and MIDI events to whichever key you need. Simply select the event you wish to transpose and right click. In the popup menu you will see an option for transpose and tune. Adjusting the transposition will repitch the audio up or down. This tool accepts numbers between -24 and +24, and is defaulted to 0. Each number is a half step up or down, which means that you can transpose an audio clip up to two octaves up or down.

For smaller pitch adjustments you can utilize the tune option. This will tune the pitch in a range of -100 to +100 cents, defaulting to 0 again. This means that you can fine tune audio up to a whole step up or down. One useful way to use this is to select and correct small portions of a recording where a specific note may be just a little out of tune. Tuning works the same for both MIDI and audio

Transposing for MIDI can work a little differently. If you select an MIDI event, right click (or under the actions menu) and select transpose, a few more options appear. You can use the sliders to easily select octave transpositions, specific intervals, or setting all of the MIDI notes to the same pitch. These are all common ways to utilize MIDI transposition.

## Lab 2

Lab Objectives:

* Field recording using a mobile recorder
* Importing audio from a device (you will not be recording directly into Studio One)
* Event-based audio editing techniques and tools within the arrange window
* Creating and editing Fades with the Arrow Tool
* _Optional: Strip Silence_

Instructions:

There are two different sets of instructions for this lab. One if your class has access to handheld, SD card recorders, and one if you will be using a cellphone.

Handheld Recorder Instructions:

1. Make sure you are able to work with your specific handheld recorder. Be sure to read through the operations manual to make sure you can create and save recordings.
    * Set the gain level to a cement amount. (ca. 5-7/10 is usually a good place to start) This is only an option on certain recorders such as the Zoom handy recorder line.
    * Make sure the bit depth is set to 16 bits or greater, and the sample rate is set to 44.1 kHz or greater.
2. Take the first half of lab time wandering around the building and immediate vicinity looking for interesting sounds. Remember to be respectful of those around you. Capture one example of each of the following on your portable recording device:
    * natural sounds - sounds that occur in nature (birds, water, tree leaves, wind, etc)
    * environmental sounds - sounds made by other humans or machines around you (talking, running, traffic, espresso machines, etc)
    * intentional sounds - a sound you make yourself that you find interesting (knocking on a metal handrail or locker, stomping in the stairwell, squeaky shoes, etc) 
3. Return to the lab with enough time remaining to import and edit your files.
4. Open your DAW, create a new song/project with the title “YourFirstNameYourLastName-Lab2”. Use the following settings:
    * Sample Rate: 44,100 Hz
    * Bit Depth: 16 Bits
    * Tempo: 120 BPM
5. Import the audio from your handheld recorder to the computer with the following steps:
    * Turn off the handheld recorder and remove the SD card
    * Insert the SD into the SD slot on your computer. You may need an adapter if your device uses microSD.
    * Locate your desired files within the folders on the SD card.
    * Drag and drop the desired files into the DAW session.
6. Look for interesting moments or sections in your files and isolate them by splicing and deleting undesired content. Tighten up the remaining audio regions by adding short Fades to the start and end of every region. 
7. _Optional: Depending on the source material, the “Strip Silence” function may work well to automate the first stage of this process. You will still need to manually clean up the regions that it leaves behind._
8. When you are finished, export the audio as instructed in “Mixdown Requirements” and submit it to your teacher.
9. As always, save a backup copy on your personal storage media. This can be a flash drive, SD card, or online cloud storage. Be sure to backup both the session AND the exported audio.

Cellphone Instructions:

1. Before starting, ensure that you are using a mobile app that is set to record in an uncompressed format such as .wav, .flac, or .aiff AND, if the options are accessible, that it is set to use a bit depth of 16 bits or greater and sampling rate of 44,100Hz (44.1kHz) or greater.
2. Take the first half of lab time wandering around the building and immediate vicinity looking for interesting sounds. Remember to be respectful of those around you. Capture one example of each of the following on your portable recording device:
    * natural sounds - sounds that occur in nature (birds, water, tree leaves, wind, etc)
    * environmental sounds - sounds made by other humans or machines around you (talking, running, traffic, espresso machines, etc)
    * intentional sounds - a sound you make yourself that you find interesting (knocking on a metal handrail or locker, stomping in the stairwell, squeaky shoes, etc) 
3. Return to the lab with enough time remaining to import and edit your files.
4. Open your DAW, create a new song/project with the title “YourFirstNameYourLastName-Lab2”. Use the following settings:
    * Sample Rate: 44,100 Hz
    * Bit Depth: 16 Bits
    * Tempo: 120 BPM
5. Import your newly recorded audio files into a location on your computer. The process for getting files off of your recording device will be a little different depending on the platform (iPhone, Android, or other). Once the files are on your computer, drag them onto new separate tracks in the arrange window.
    * Android instructions (Skip the installation step - the Android File Transfer application will already be installed on your lab computer.)
    * Apple Music Memos Instructions (You can use either the Share via email or Share via iTunes on a Mac options, though the latter requires an iPhone USB cable and knowledge of iTunes.)
    * Attach the files to an email and send it to yourself. Open on your computer and download.
    * Upload to a cloud storage service such as google drive or dropbox, then download on your computer.
6. Look for interesting moments or sections in your files and isolate them by splicing and deleting undesired content. Tighten up the remaining audio regions by adding short Fades to the start and end of every region.
7. _Optional: Depending on the source material, the “Strip Silence” function may work well to automate the first stage of this process. You will still need to manually clean up the regions that it leaves behind._
8. When you are finished, export the audio as instructed in “Mixdown Requirements” and submit it to your teacher.
9. As always, save a backup copy on your personal storage media. This can be a flash drive, SD card, or online cloud storage. Be sure to backup both the session AND the exported audio.

Mixdown requirements:

* File name: YourFirstNameYourLastName-Lab2.
* Format: Wave or MP3 at 44.1kHz sampling rate and 16-bit resolution (128 kbps for MP3 files). Just one, you don’t need to mixdown two files.
* Do not adjust loudness.
* Make sure to export the Main output.
* Be sure that the duration of the resulting audio file matches what you expect. Each sample should play one after the other, with no more than 2 seconds of silence between each one.
* Be sure to follow your teacher’s guidelines for file submission.



</section>