Timestreching is taking an audio file and slightly speeding it up or slowing it down in order to match the tempo of the Studio One session. Adjusting the speed of the file through timestreching will not alter the pitch of the original file. Excessively large stretches may still create noticeable pitch discrepancies, so it is best to utilize small amounts of stretching when needed. One example is a 4 bar drum loop recorded at 120 bpm being stretched to match a session tempo up to 20 bpm off from the original. This will allow the source loop to still be 4 bars long at a variety of tempi. You can set the timestreching manually or automatically.

To manually set the timestreching of an audio event, begin with the arrow tool. Float the mouse cursor to the left or right edge of the target Audio Event and hold Alt/Option on the keyboard. The Timestretch tool appears, and looks like an analog clock face. Then you can click on the edge of the Event and drag left or right to timestretch the Event, making it shorter or longer. In this case the length of the Event changes, using the Speedup factor, but the pitch of the audio remains the same. Only the Event that you selected for timestreching is affected.

Speedup factor is a timestreching function for making an audio clip shorter or longer while maintaining its pitch. This is used to stretch Audio Events when you do not wish to define a tempo for the original audio clip, which would affect all Events associated with that clip. The Speedup factor value changes during manual timestreching, and it also can be entered manually in the Event Inspector. Values greater than 1 decrease the length of the clip, while values less than 1 make the clip longer.

Note that manual timestreching can not be used on an Audio Event containing a sliced loop.

For automatic timestreching, you must open up the track inspector by selecting the desired track and pressing the F4 key on your keyboard. You can then select one of three timestreching option from the track inspector: 

Don’t Follow: Events on this Track are independent of the Song tempo. They are never moved or stretched automatically.
Follow: The start positions of Events on this Track are tied to the musical grid. Thus, the Events move when the Song tempo changes but they are not stretched.
Timestretch: Event start positions follow the Song tempo, as in Follow mode. In addition, the Events are stretched to fit the Song tempo.

You can also set the timestretch to one of four different modes depending on what kind of sounds you are working with and the desired effect. These modes are:
Drums: Use this optimized mode on any percussion track to achieve the best results when stretching percussive audio. This mode uses the Elastique Direct algorithm.
Sound: Use this general mode on any other type of track. This mode uses the Elastique Direct Formant algorithm.
Solo: Use this optimized mode on any solo instrument or vocal track to achieve the best results. This mode uses the Elastique Pro Monophonic Formant algorithm.
Tape: In this mode the track audio follows the song tempo by changing the sample playback rate. This results in the pitch moving up or down when the tempo changes, sort of like changing the speed control on a tape deck. Try this with drum loops or other samples when the pitch doesn't need to be exact.

