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

Lastly, to program any customizable knobs, buttons, or sliders on your controller it is very simple. First, notice the top-left of the screen. Here you will see a window containing the last control input from the MIDI controller as well as the last parameter you interacted with in Studio One. Simply adjust the desired parameter, then adjust the button/key/slader/kbob you wish to map it to. When both of the elements in the boxes are correct, click on the arrow in between the two elements to map it. Now, whenever you use that specific control on the MIDI controller, the mapped parameter will automatically adjust itself. This is super useful for controlling parameters such as volume and panning quickly and easily no matter which screen you are looking at in Studio One.

A video breakdown of the above steps can be found here: 

<iframe width="560" height="315" src="https://www.youtube.com/embed/Wc-SOxMVIkU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


For more information about connecting MIDI controllers to your device, check out the [Studio One 6 online manual](https://s1manual.presonus.com/StudioOneReferenceManual.htm#Setup_Topics/Set_Up_Your_MIDI_Devices.htm?TocPath=Setup%257C_____4).
