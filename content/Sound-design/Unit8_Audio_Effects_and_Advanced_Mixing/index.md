# Unit 8: Audio Effects and Advanced Mixing

This unit goes over how you can process your audio files in order to further enhance your mixes and make new sounds. We will tour the built-in mixing console and audio effects present in Studio One Professional, more advanced mixing practices, and a few helpful tips for creating your music before diving into practice!

## Mixing Console

The mixing console is the most important tool in Studio One for creating your own sounds and audio mixes. It displays everything that is happening in the DAW at once in a condensed, easy to understand format. However, if you have never worked with an analog audio mixer, the layout may still be a little confusing so let’s take the time to break it down.

Parts of the Mixing console:

* The mixing console is accessed by the Mix button in the bottom right of the screen. It can be popped out, so I recommend putting it on a second monitor if you have one. Every channel, which is everything with audio in the project, will appear here from left to right. You will notice that each channel has basically the same elements, and the pattern repeats for everything in your session. 
*   Much like an analog mixer, you can think of the audio signal as moving from the top of the mixing console to the bottom. When the event is played back, the signal will enter the mixer and then be sent through the inserts. These are the audio effects that you are inserting into the signal pathway in order to alter the sound. 
* Moving down, the next section is for sending audio to other places in the mix. This is generally used for parallel processing, grouping audio channels together, or sidechaining audio effects.
* The next section shows the audio channel’s input and output. This will usually indicate which interface microphone channel you are using, and if the audio is being sent to the Main output channel or somewhere else. Underneath this is a graphic representation of the channel panning. You can change this by dragging the blue bar left and right.
* The four buttons below the channel IO are Mute, which silences the channel when active. Solo, which silences all OTHER channels when active. Record Arm, which flags a track to record its input when the record button is hit. Monitor, which feeds the input for that channel directly into the Main output channel.
* The slider controls the output gain for the channel and is the most noticeable feature of each channel. Moving it up makes the channel louder, but it is better practice to make things softer. This way you can balance things without distortion from making it too loud. Remember, if you can’t hear something, it is usually a better idea to make other things quieter before you make the first sound louder.
* On the left of the Mixing console you will see several options for showing or hiding various things in the mixer. What was listed above is the default appearance, but you can choose to shore more or less information depending on your needs.  

Types of Tracks:

There are a few different kinds of channels that are present in the Mixing console. These are audio, instrument, Bus, FX, VCA, and Aux. Audio and Instrument are basically the same as what appears horizontally in the main window. These will appear automatically as you add more tracks. Some instruments, such as ImpactXT, will have multiple channels but only one track. A Bus channel serves as a collection or sub-mix. You can send various audio channels to a bus in order to process all of them the same way or adjust their volume all at once with a single fader. This is useful for things like drums where you may want to control the volume for all of a part at one time.

* FX channels are used for parallel processing. This means that you are sending the same source through two different effect chains at the same time, and that each one has its own independent volume slider. This can be useful for adding effects like reverb to an FX track, then automating how much is present by adjusting the volume slider. You can send to the FX channel from the source channel’s send section.
* VCA channels offer another way of working with groups of channels. By sending audio to a VCA channel, you can create a mix of the various instruments in the group, and then adjust all of their volumes without altering the balance with the VCA slider.
* Aux channels will likely not be used much in this course, but they are utilized for receiving audio from external sources. If you connect a hardware synthesizer instrument or any other kind of audio to your audio interface, you can utilize an Aux channel. The Aux channels can be saved as presets so you can simply drag and drop them brom the browse window to begin utilizing the input. When making the Aux channel you will need to set up the hardware input as a unique instrument, which is a process that varies depending on your operating system. You could also set up a cross-software Aux channel using the same process. For a more detailed look at making and utilizing Aux channels in Studio One, [check out this blog post by Presonus](https://blog.presonus.com/2021/12/10/sowhats-deal-aux-channels/).


## Audio Mixing

Audio Mixing is a skill and art that takes years of practice to fully develop. Don’t worry if that sentence makes the idea seem intimidating. The goal of this page is to break down the concept of audio mixing and go over some common techniques in order to get you started with making your own unique sounds and music. The experience will come as you do more mixes and get feedback on your projects!

In general, mixing audio is exactly what it sounds like: taking multiple audio sources and combining them into a cohesive final product. This involves adjusting the levels of various sounds, altering timbres with effects to create the desired effects/blending, automation of parameters, and more.

Studio One 6 does its mixing through the mixing console, which can be brought up with the Mix button in the bottom right of the screen. If you have a second monitor available, I recommend popping the window out and keeping it on the second monitor as the mixing console can take up a lot of screen space. Here we will be able to monitor and control everything that is part of our mix, just like a physical mixing console. Let’s start with the most noticeable feature of a console, the faders.

Each channel in your project will have a fader in the mix console. This fader controls the volume of everything on that channel, and is the last part of the signal chain before it is sent to the main output. You can utilize this to make sounds louder or softer to create the balance that you want. Notice that by default, each channel begins at 0dB (also called Unity Gain). This means that there has been no alteration to the original volume of the source. If you pull a slider down into the negative values, the sound will get softer, and pushing it up into the positive values will make it louder. Because of how the human ear hears volume, a change of approximately 10dB will be perceived as the sound doubling or halving in volume.

You may notice that on these faders, the majority of the fader is below 0 dB. This is in part because if you boost everything, you will quickly run into clipping and distortion. In general, you will be making sounds softer in order to balance them without making things too loud. You can still boost things past Unity Gain, but there is much less headroom when doing so. If you have a sound that is too quiet, it is usually good practice to make other elements in your mix quieter instead of just making the problematic element louder. 

In the Mix Console you can also control the panning of an audio channel. This value can be viewed as a ratio between the left and right speakers. When a sound is panned hard right it is only coming out of the right speaker, hard left for the left speaker, and when panned center (default) it will be coming out of both speakers equally. Panning can be controlled in the Mixing console through the blue vertical bar above the fader. Simply drag it to the left or right depending on your desired panning.

Audio effects are used in order to change the recorded sound in order to develop your desired mix. Perhaps you want to add reverb to the vocals, distortion to the guitars, or an echo on just the chorus, and only in the horns. All of these and more are possible through the mixing console. In Studio One 6 you can add effects to the Inserts section of the mixing console. You can either drag and drop them from the browser window or click the plus icon next to the word Inserts to select your sedated effect from a list. Once added, the audio signal will be passed through the effect before being panned and having its volume adjusted with the fader. Each audio effect has its own unique interface that allows you to control exactly how the effect is altering the sound. When adding multiple effects, they are all applied to the audio signal in series. Meaning the sound will go through the topmost insert, then the second one, and so on down the list of however many you may have. Depending on the effects in use, changing the order of the inserts could potentially create a greatly differing sound.

The last general concept we will discuss in this section is routing audio. In the mixing console you can control exactly where audio comes from and goes within the DAW. You can change which interface input a channel is connected to, group up multiple channels and send them to different places, create sub mixes and more. One of the more useful things that can be done with this is to create a Bus channel and send multiple audio sources to it. Then you can easily boost, cut, or process multiple sounds at once. It is common to group up similar instruments such as the drums or guitars into a group.

The [Studio One 6 online manual has an entire chapter on mixing and the mix console](https://s1manual.presonus.com/StudioOneReferenceManual.htm#Mixing_Topics/Chapter-Mixing.htm?TocPath=Mixing%257C_____0). Be sure to check it out for more information on the topics introduced here, as well as any other features of the Mix window!

### Handy tips:

While there is no ‘correct’ way to mix, there are a few general practices and techniques that you can utilize in order to make your mixes better. Try a few of these out, but remember, as long as the mix sounds like you want it to, then it is doing its job.

* Minimize overlapping:
	The main goal of mixing is to combine all of the parts of your music together so that everything can be heard in a balanced way. Nothing is covering up anything else, and is nice and clear. To help with this, it is a good practice to minimize any overlapping in both frequency content and panning. When using an equalizer, in addition to shaping the sound, it is handy to remove problematic frequencies that could interfere with other instruments. For example, if you want to mainly hear the bass guitar as the bass voice of a song, you may need to remove some of the bass frequencies of other instruments so that they don’t cover up the desired sound as much. If you have multiple instruments with similar ranges and sounds, such as having two guitar parts, try panning them to different locations in order to clearly separate them  for the listener. This way both parts can be heard without them interfering with each other as much.
* Parallel Processing:
	As mentioned above the audio inserts are applied to a sound source in series. However you can easily create a new channel and process the sound in parallel instead. To do this, right click and create a new FX channel, then on the sound source, click the little + icon next to the sends section and select your new channel. Now you can add an effect chain to the FX channel and you will hear both the original sound and the altered sound in the final mix. This is useful if you have a unique effect you want to add to a sound only at certain times in the song. Simply bring up the FX channel fader when you want more, and lower it when you want less. Try it with effects like reverb and compression!
* Automation:
	While not strictly part of the Studio One mixing console, remembering to automate your mix is necessary in creating a cohesive mix from start to finish. It is basically impossible that all of your recordings will be perfectly balanced for the entire duration of your song, especially once you begin adding effects or recordings from multiple sources into the mix.  While you can automate almost everything in the mix, adding slight automatons to just the volume faders is probably the most effective automation you can do. You can mark different sections of the song and have the mix automatically change based on the time. This way perhaps you could have the drums get louder in a chorus, or backing vocals fade out over a verse. At the very least it will allow you to maintain balance between parts regardless of the volume of the source recording.

### Test Your Knowledge!

Which type of channel in the Mixing console is mainly used for audio processing with effects?

- [[ ]] Main
- [[ ]] Aux
- [[ ]] Bus
- [[ ]] VCA
- [[X]] FX

## Studio One 6 Builtin Audio Effects

A software audio effect is an algorithm that alters how the computer plays back the audio. The end result is a change in how we hear the sound. Using these algorithms we can create effects like reverb, distortion, filters, and more.

Studio One 6.2 includes a handful of common audio effects included with the software. Here we will be going over each of them and what they do. If you have additional audio effects you will see them in the browse window. We will only be covering effects present in ALL versions of Studio One 6. If you want more info on effects included on only the Professional version, check out the [Studio One 6 online manual](https://s1manual.presonus.com/#Built-In_Effects_Topics/Chapter-Built_In_Effects.htm?TocPath=Built-In%2520Effects%257C_____0)!

To see all of your audio effects, open the browse window and click on Effects. You can arrange them however you want, but we will be going over the ones in the default Presonus folder. For more information on these effects, check out the [Studio One 6 online manual](https://s1manual.presonus.com/#Built-In_Effects_Topics/Chapter-Built_In_Effects.htm?TocPath=Built-In%2520Effects%257C_____0)!

### Monitoring Effects

The first category of ‘effects’ we will be looking at generally do not alter sounds like the others, but are implemented in the same way. These effects are used for monitoring various aspects of the sound.

* Phase Meter
    This effect displays the phase correlation of the various channels in your mix. This is useful for identifying when different sources are out of phase and canceling each other out. Check out this video for a breakdown of the Phase meter and how to read its interface:
        !?[phase-meter-video](https://youtu.be/PdJ3X31VtVM)
* Spectrum Meter
    The spectrum meter will look at any incoming audio and display the frequency component of that sound. The frequency is represented on the horizontal axis, and the volume is represented on the vertical axis.The higher a line, then the louder that specific frequency is. When using the spectrum meter you can change how the plug-in is displaying the values, as well as which sounds the plugin is looking at. This interface is very similar to the ProEQ plug-in, but without the filters.
* Tuner
    This effect also analyzer frequencies in a sound source, but it compares it to musical notes and returns the closest note, as well as the deviation from that note in cents (1/100th of a half-step). This is used like a hardware instrument tuner for  making sure your performers are all tuned together, or identifying problematic notes to fix with other plugins 
* Level Meter
    Displays the loudness of the incoming audio. Measurement scales can all be adjusted in the plug-in. You can see average vs true peak values, as well as the phase correlation.
* Scope
    A virtual oscilloscope. Basically everything a hardware oscilloscope can do is present in this plug-in
* IR Maker
    Creates impulse responses for use with the Open Air and Ampire plug-ins. This is generally not used in this course, but check out the [online manual for the steps on how to create your own IR](https://s1manual.presonus.com/#Built-In_Effects_Topics/Analysis_and_Tools.htm?TocPath=Built-In%2520Effects%257C_____2).
* Mix Tool
    Performs general tasks such as adjusting gain, inverting phases, swapping Left and Right channels and more when mixing audio.
* Tone Generator
    This is the only effect in this category that actually produces a sound. You can utilize this to setup specific tones and their characteristics. While it can be used to create content by feeding it into a mix, it is generally designed for setup and troubleshooting

### Delay Effects

The following Effects all delay an audio signal in different ways:

* Analog Delay
    This plug-in replicates a physical tape delay and can optionally be synced to the project’s tempo. It includes a filter, LFO, stereo panning controls, and the speed of the virtual tape.
* Beat Delay
    A delay which syncs to the tempo of the song. It does not include the coloring tools and LFO of Analog Delay.
* Groove Delay
    This delay has four delay lines (you will hear the original sound a total of 5 times) instead of the single delay line of the other effects. This effect will sync each line to the tempo, and can have the volume and panning set for each line individually. This allows you to create unique, evolving delays throughout your music.


### Distortion Effects

The following Effects all distort the signal in different ways:

* Ampire
    Ampire is a large effect with many sub categories. Here we will briefly go over them, but be sure to check out the [manual for more information](https://s1manual.presonus.com/#Built-In_Effects_Topics/Distortion.htm?TocPath=Built-In%2520Effects%257C_____4) if you need it.
    Ampire is used to model various combinations of guitar and bass amps. You can utilize this to create an amplifier for a recorded guitar, or to make a MIDI guitar sound more realistic. 
    In the toolbar you can adjust what type of amp is being used, the cabinet, and the virtual microphone placement in order to create your custom sound.
    You can also include a pedal board full of effects that will be applied to the sound before it reaches the amp. There are a large number of modeled stomp-boxes, but they are all commonly used sounds from real-world boxes. Generally speaking, a lot of the effects listed here also have a similar version that can be implemented inside of Ampire.
* BitCrusher
    Bit crusher intentionally lowers the bit-depth of the incoming audio in order to create distortion. By combining overdrive, bit-depth reduction, downsampling and clipping, a wide variety of potential sounds is possible.
* Red Light Distortion
    This is a more generalized distortion designed to replicate analog hardware distortion effects. 


### Volume Effects

The following effects all alter the volume of the signal in different ways:

* Compressor
    A compressor works by reducing the volume of an audio signal when it passes a specific threshold. This is useful for both making loud sounds quieter and soft sounds louder.
    You can use this to make a soft sound louder by compressing the louder parts of the signal, then boosting the entire sound as a whole to match the desired level.
* De-Esser
    This effect is a filter designed to specifically target undesired sibilance in a recording. By fine tuning this to match the noisy elements of a recording, you can cut the volume of the problematic noise and leave the other sounds untouched.
* Expander
    Works like a compressor, but the opposite. It generally works by lowering the volume of quieter sounds in order to increase the dynamic range of a signal.
* Gate
    Gates only allow sounds of a specific volume to pass through. This is useful for eliminating low-level noise in a sound file.
* Limiter
    A limiter will look at a sound and keep it from exceeding a volume threshold. This is useful for avoiding clipping or pushing the volume of a sound.
    Check out the video manual for the Limiter effect:
        !?[limiter-manual-video](https://www.youtube.com/watch?v=7eE5lknIIL8)
* Pro EQ
    An equalizer is a series of filters designed to boost or cut various frequencies within a sound. The ProEQ effect has eight different frequencies that it can use at once.
    You can customize the specific frequency of each band, as well as the general shape of each band. EQs are useful for removing frequencies that conflict with other tracks or are otherwise problematic, or boosting desired frequencies in a sound. 
    You can see the levels of the frequencies overlaid with the visual representation of the EQ filters. This view is essentially the same as the LEvel Meter plug-in.
    Check out the video manual for a more detailed breakdown of how to utilize an equalizer:
        !?[proEQ-manual-video](https://www.youtube.com/watch?v=1fVLvFWlU9w)


### Mastering Effects

These effects are all generally used in the Mastering process in various ways:

* Multi-band Dynamics
    Multi-band dynamics is essentially a combination of the compressor and the Pro EQ. This effect allows you to create 5 different compressors, each one focusing on a different frequency range of the incoming sound.
    This effect is useful for applying compression to a completed mix, and is used to slightly boost or cut various areas of the song as a whole
* Tri-Comp
    Tri-Comp is essentially the same thing as Multi-Band Dynamics, but with less customizability.
    Tri-comp only has 3 bands instead of 5.

### Mixing Effects

These effects are generally used when mixing audio:

* Binaural Pan
    Is used to adjust the specifics of panning.
    Can be used to increase or decrease stereo width.
    Check out this summary video:
        !?[binaural-pan-video](https://www.youtube.com/watch?v=fJ09Pp81RLE)
* Channel Strip
    Combines three effects in one: a low-cut filter, dynamics processor, and three-band parametric EQ.
    This is used to color the sound. Hardware channel strips will utilize these effects to process the sound before it is recorded, but when a virtual effect is used it can be easily adjusted and removed.
    Use this effect to give your recordings a complementary setup before any other effects.
    This is also useful for adding several effects at once and saving computer memory and processing power.
* Dual Pan
    Offers more panning control
* Fat Channel
    Fat Channel functions almost identically to Channel Strip, except Fat Channel is a complete virtual version of the channel strip found on the PreSonus StudioLive III line of mixers.
    Fat Channel replicates hardware channel strips and allows you to customize which effects are being used and the order of those effects. 
    Fat Channel has a total of five different effect slots, and each effect has multiple options for how it functions.
    See the [online Studio One 6 manual](https://s1manual.presonus.com/#Built-In_Effects_Topics/Mixing.htm?TocPath=Built-In%2520Effects%257C_____9) for more information on the specifics of these effect options.
* Splitter
    Splitter will take an incoming audio channel and split it to allow for parallel processes to happen before summing the two channels back together again.
    This is useful for combining multiple effects on a sound source that you do not want to affect each other, as well as the mixing between those effects.
    Check out this video on Splitter from Presonus:
        !?[splitter-video](https://youtu.be/ohfNHuKq_Eg)


### Modulation Effects

These effects all Modulate sounds:

* Autofilter
    Autofilter is a set of two different filters that will automatically be applied to the sound source with an LFO to control the filter. This can create a repeating texture that changes over time.
* Chorus
    A chorus will delay a signal slightly and detune the delays in order to make a single source sound like multiple.
    This chorus has up to three voices and is generally used to fill out the sound.
* Flanger
    Flangers work by splitting an audio signal into two identical signals. Then apply a varying, short delay to one signal, and feed its output back in varying amounts. The two signals are then mixed back together.
    Flangers are commonly used to give guitars unique, evolving textures.
* Phaser
    A phaser applies multiple all-pass filters in order to change the phase of a signal without changing the pitch content. THese filters slightly delay the sound, causing frequencies to fight with each other, boosting and cutting various ones for a unique effect.
* Rotor
    Rotor replicates a spinning horn present in some kinds of speakers and amplifiers. The result is a unique timbre that warbles along with the virtual spinning of the rotor.
* Vocoder
    A vocoder works by combining two sounds. Basically breaking one sound into its frequency components, then adjusting the other sound to match the various volumes of those frequency components.
    Vocoders are generally heard on vocal recordings and can give the voice a unique texture or create harmonies from a single source.
* X-Trem
    Creates a tremolo effect by modulating the amplitude of the incoming signal.


### Reverb Effects

These are all of the included Reverb effects in Studio One 6.2:

* Mixverb
    Simple reverb utilizing delay lines.
* Open Air
    Convolution Reverb that takes impulse responses (IR) and utilizes them to replicate real-world locations.
* Room Reverb
    Room reverb sits in between the two previous reverbs. It models virtual rooms and utilizes those parameters to control the delays of the reverb effect.

Hardware Effects can be utilized with the Pipeline effect. Generally this is not a part of the course unless you or your classroom has access to hardware audio effect units. This is usually ignored because of how expensive and delicate these units can be. For more information on Pipeline, check out this video from Presonus:

!?[pipeline-manual-video](https://www.youtube.com/watch?v=us-3-KSd-sI)

### Test Your Knowledge!

Which of the effects below do _not_ alter the sound entering the effect in any way?

- [[ ]] Groove Delay
- [[ ]] Sample One
- [[ ]] Room Reverb
- [[X]] Phase Meter
- [[ ]] Pro EQ

## Lab 8

Objectives:

* Practice with Plugins as inserts
* Practice with routing and use of plugins on a submix/bus
* Practice with routing and use of plugins on an aux send

Instructions:

1. Open your DAW, create a new song/project with the title “YourFirstNameYourLastName-Lab8”. If prompted, use the following settings:
    * Sample Rate - 44.1kHz
    * Resolution - 16 bit
    * Tempo - your choice (try to get away from 120)
2. Create an Insert
    * Provide at least one example of a track with a plugin applied as an insert. Choose a plugin appropriate for this signal flow - e.g. EQ, distortion, etc.
3. Create a submix
    * Provide at least one example of two or more tracks submixed to a bus channel. A submix is created when the output of multiple channels are sent to a bus track rather than the main outs. Once you have a submix set up, apply a plugin on the bus channel appropriate for this signal flow - e.g. EQ, compression, etc.
4. Create an aux send
    * Provide at least one example of one or more tracks sent to a bus or FX channel using aux sends. Apply a plugin to the bus/FX channel appropriate for this type of signal flow - e.g. reverb, delay, etc.
5. When you are finished, export the audio as instructed in “Mixdown Requirements” and submit both to your teacher.
6. As always, save a backup copy on your personal storage media. This can be a flash drive, SD card, or online cloud storage. Be sure to backup both the session AND the exported audio.



Mixdown Requirements:

* File name: YourFirstNameYourLastName-Lab8.
* Format: Wave or MP3 at 44.1kHz sampling rate and 16-bit resolution (128 kbps for MP3 files). Just one, you don’t need to mixdown two files.
* Do not adjust loudness.
* Make sure to export the Main output.
* Be sure that the duration of the resulting audio file matches what you expect. Your Lab project should be approximately 8 bars in duration.
* Be sure to follow your teacher’s guidelines for submission.

 