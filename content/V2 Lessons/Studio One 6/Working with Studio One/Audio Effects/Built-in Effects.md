A software audio effect is an algorithm that alters how the computer plays back the audio. The end result is a change in how we hear the sound. Using these algorithms we can create effects like reverb, distortion, filters, and more.

Studio One 6.2 includes a handful of common audio effects included with the software. Here we will be going over each of them and what they do. If you have additional audio effects you will see them in the browse window. We will only be covering effects present in ALL versions of Studio One 6. If you want more info on effects included on only the Professional version, check out the [Studio One 6 online manual](https://s1manual.presonus.com/#Built-In_Effects_Topics/Chapter-Built_In_Effects.htm?TocPath=Built-In%2520Effects%257C_____0)!

To see all of your audio effects, open the browse window and click on Effects. You can arrange them however you want, but we will be going over the ones in the default Presonus folder. For more information on these effects, check out the [Studio One 6 online manual](https://s1manual.presonus.com/#Built-In_Effects_Topics/Chapter-Built_In_Effects.htm?TocPath=Built-In%2520Effects%257C_____0)!

The first category of ‘effects’ we will be looking at generally do not alter sounds like the others, but are implemented in the same way. These effects are used for monitoring various aspects of the sound.

* Phase Meter
    This effect displays the phase correlation of the various channels in your mix. This is useful for identifying when different sources are out of phase and canceling each other out. Check out this video for a breakdown of the Phase meter and how to read its interface:
    <iframe width="560" height="315" src="https://www.youtube.com/embed/PdJ3X31VtVM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
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

The following Effects all delay an audio signal in different ways:

* Analog Delay
    This plug-in replicates a physical tape delay and can optionally be synced to the project’s tempo. It includes a filter, LFO, stereo panning controls, and the speed of the virtual tape.
* Beat Delay
    A delay which syncs to the tempo of the song. It does not include the coloring tools and LFO of Analog Delay.
* Groove Delay
    This delay has four delay lines (you will hear the original sound a total of 5 times) instead of the single delay line of the other effects. This effect will sync each line to the tempo, and can have the volume and panning set for each line individually. This allows you to create unique, evolving delays throughout your music.

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

The following Effects all alter the volume of the signal in different ways:

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
    <iframe width="560" height="315" src="https://www.youtube.com/embed/7eE5lknIIL8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
* Pro EQ
    An equalizer is a series of filters designed to boost or cut various frequencies within a sound. The ProEQ effect has eight different frequencies that it can use at once.
    You can customize the specific frequency of each band, as well as the general shape of each band. EQs are useful for removing frequencies that conflict with other tracks or are otherwise problematic, or boosting desired frequencies in a sound. 
    You can see the levels of the frequencies overlaid with the visual representation of the EQ filters. This view is essentially the same as the LEvel Meter plug-in.
    Check out the video manual for a more detailed breakdown of how to utilize an equalizer:
    <iframe width="560" height="315" src="https://www.youtube.com/embed/1fVLvFWlU9w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> 

These effects are all generally used in the Mastering process in various ways:

* Multi-band Dynamics
    Multi-band dynamics is essentially a combination of the compressor and the Pro EQ. This effect allows you to create 5 different compressors, each one focusing on a different frequency range of the incoming sound.
    This effect is useful for applying compression to a completed mix, and is used to slightly boost or cut various areas of the song as a whole
* Tri-Comp
    Tri-Comp is essentially the same thing as Multi-Band Dynamics, but with less customizability.
    Tri-comp only has 3 bands instead of 5.

These effects are generally used when mixing audio:

* Binaural Pan
    Is used to adjust the specifics of panning.
    Can be used to increase or decrease stereo width.
    Check out this summary video:
    <iframe width="560" height="315" src="https://www.youtube.com/embed/fJ09Pp81RLE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
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
    <iframe width="560" height="315" src="https://www.youtube.com/embed/ohfNHuKq_Eg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

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

These are all of the included Reverb effects in Studio One 6.2:

* Mixverb
    Simple reverb utilizing delay lines.
* Open Air
    Convolution Reverb that takes impulse responses (IR) and utilizes them to replicate real-world locations.
* Room Reverb
    Room reverb sits in between the two previous reverbs. It models virtual rooms and utilizes those parameters to control the delays of the reverb effect.

Hardware Effects can be utilized with the Pipeline effect. Generally this is not a part of the course unless you or your classroom has access to hardware audio effect units. This is usually ignored because of how expensive and delicate these units can be. For more information on Pipeline, check out this video from Presonus:

<iframe width="560" height="315" src="https://www.youtube.com/embed/us-3-KSd-sI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
