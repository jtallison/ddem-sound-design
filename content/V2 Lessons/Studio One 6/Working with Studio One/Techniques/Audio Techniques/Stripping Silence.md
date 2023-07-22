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
