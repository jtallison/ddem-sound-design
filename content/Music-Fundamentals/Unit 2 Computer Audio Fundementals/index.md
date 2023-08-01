# Unit 2: Computer Audio Fundementals

<section>

## Physics of Sound

Speaking from a purely scientific viewpoint, sound is the transfer of energy from one source to another through pressure waves vibrating against various elements in the environment. These waves can vary in size and frequency, but when they are detected by a person, we are hearing a sound. 

These vibrations travel at different rates through different media. When a person is referring to the speed of sound, they are usually talking about the speed of sound in air. Below isa chart showing the approximate speed of sound through various different media. Generally speaking, the denser the material, the quicker sound travels through it, but the quicker the energy decays.

In order to create these sound waves, something must first begin vibrating. The oscillations of this movement cause the air molecules around the source to get pushed into each other. The molecules then bounce off each other and into the next molecule. This process will repeat until the sound wave is absorbed by something else. 

The number of times per second (Hz) that these waves arrive at the human ear is called the frequency. Humans can, on average, perceive a sound that is within the range of 20-20,000 Hz. If a sound is outside of that range, then the sound is still there, humans just are unable to hear it. The range of human hearing will vary from person to person, and factors such as the volume of the original sound, distance from the sound, a person’s head shape, and age can all affect the range of hearing. Most people begin to lose their ability to perceive the higher end of this range as they reach adulthood.

[video showing full range]

In order to form a musical pitch, specific frequencies must be produced on an instrument. Because it is much simpler to refer to a note as “A” instead of 440Hz, people will utilize a repeating alphabetic scale to refer to certain frequencies. It is important to know that humans perceive frequency on an exponential scale. Meaning that every octave a pitch increases, the frequency must double. For example:

* A2: 110 Hz
* A3: 220 Hz
* A4: 440 Hz
* A5: 880 Hz
* And so on

When looking at music notation, every line and space on the staff is referring to a specific frequency to be created by the performer. 

Alongside the pitch of a sound is its volume. While the number of times an air pressure wave hit our ears per second is perceived as a pitch, the size of those waves is largely responsible for how we perceive volume. Generally speaking larger pressure waves = louder sound. The size, or amplitude of these waves is measured in decibels of air pressure (dB). Generally speaking, sounds exceeding 100 dB will cause discomfort to most listeners, and anything above 120 dB can cause pain and hearing damage. These ranges are approximate and do not take into account the listening time. While a shotgun blast is quite loud, a single instance of being exposed to that volume may cause less long-term damage than listening to music at 90 dB over a long period of time. When in doubt, it is important to take breaks from listening, and investing in hearing protection. It becomes much harder to create good music when you are unable to hear what you are doing.

By themselves, sound waves are just repetitions of pressure traveling through the air. It is the human ears and brain that are responsible for allowing us to hear and perceive different sounds. As the sound waves travel to us, the outer part of our ear, called the Pinna, acts like a satellite dish to gather the incoming waves and funnel them into the skull. (the majority of the human ear is inside of your head)

Inside of the ear the sound waves eventually hit the eardrum, or tympanic membrane, which further collects and funnels the vibrations through a series of bones to a small organ called the cochlea in the inner ear. The cochlea is filled with fluid and nerve endings that help the brain to interpret the incoming sound by acting like a filter. Sound waves of different frequencies will travel different distances along the cochlea and stimulate different nerves. This means that a 40 Hz sound and a 1000 Hz sound are stimulating different pathways to the brain, allowing us to perceive them as different pitches. A louder sound will also cause more stimulation of these nerves than a quieter sound.


## Computer Audio

Once a sound wave has been converted into electricity it can either be recorded or amplified for use in a live performance, however in modern instances, most recordings are done by computers. In order to create an audio file that can be worked with in a DAW and played back on other devices, the electric signal must be digitized. In order to do this, the computer needs a special circuit called the Analog-to-Digital Converter (ADC). The ADC takes a sample of the incoming electric current, determines the level of the current at that time, and saves the value as a number. This process happens thousands of times every second, and is called the sampling rate.

The standard audio sampling rate is 44,100 Hz, however for higher quality recordings this can be increased. 48,000 and 96,000 are common high-definition sample rates. As you might expect, increasing the number of samples will increase the size of the file. Heavily summarized, the reason that the sample rate is so high is that in order to replicate the frequencies in a recording, a sample rate must be at least twice as high as the original frequency. At 44,100 Hz, all of the general range of human hearing is covered. For more information on this phenomena, check out the Nyquist theorem.

When taking a sample the ADC must be able to save each sample as a number. The total number of options for these numbers is referred to as the bit-depth. Standard audio has a bit-depth of 16 bits. That is 216, or 65536 potential options. As the bit-depth increases, the computer is able to more accurately represent the original file, similar to an image rendered at  480p versus an image rendered in 4k. Classic 8-bit audio sounds have their unique timbre in part because of the lower bit-depth.

Once the file has been made it can be freely edited within the computer. While a person could manually edit the individual sample values, at a minimum of 44,100 values per second, this is not practical or recommended. Instead you can utilize a DAW in order to build up and edit multiple recordings at once into a single new file. When playing back an audio file, a separate circuit called the Digital-to-Analog Converter (DAC) is used to achieve this. The DAC will read the numbers of the sound file in order and use that to calculate an electronic voltage. This voltage is then output to a speaker.

A standard speaker works like a dynamic microphone, just in reverse. An electric current is fed into a wire. This wire is wrapped around a magnet and connected to a diaphragm. As the electric current changes, this causes fluctuations in the magnetic field, moving the connected diaphragm back and forth. This movement pushes the air molecules in front of the speaker, resulting in sound waves that can be heard by a listener.




</section>