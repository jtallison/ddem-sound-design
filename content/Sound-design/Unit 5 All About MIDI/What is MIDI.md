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
