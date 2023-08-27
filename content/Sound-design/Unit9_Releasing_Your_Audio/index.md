# Unit 9: Releasing Your Audio

This unit will discuss both copyright concerns as well as the mastering process so that you can potentially release music that your create online in the future. Following the copyright discussion we will explore the Studio One 6 Project page as well as how to utilize it for mastering for a release on common online streaming platforms such as Spotify, Youtube, and SoundCloud.

## Your Music & Copyright

We have not brought up copyright in this class so far because generally what we make is allowed under the educational use clause. However, there are some important things to bring up if you want to release your audio to the wider public.

The person who makes the original music is the owner. If released by a publishing company, then the publisher is usually the owner of the track. If you utilize any content that was not created by you, it is important to properly credit the original artist. If you don't do this, you may be asked to take down the song, have a copyright strike, or be sued by the owner. Best to avoid that and only post original, licensed, or public domain content.

The opposite of this is also true. Anything you create is your intellectual property and cannot be used for monetary gain without your approval. Some platforms like YouTube will automatically check if something violates copyright, but if you come across an unauthorized use of your original content, don't hesitate to claim that to the platform.

In these short videos by the Berklee College of Music, copyright and audio sampling is wonderfully broken down and explained:

!?[berklee-copyright](https://www.youtube.com/watch?v=tQbJLvli9AY) !?[berklee-sampling](https://www.youtube.com/watch?v=RwR5PcddsIc)

You can check out the [full 6-part playlist on musical copyright here](https://youtube.com/playlist?list=PL1wHeEmBdcWTFbkxKWZ8A9BQGvxv74gPw).

## Studio One 6 Project Page

For 99% of this course we have been using the Studio One Song editor view. This is used for creating various elements in a new mix and recording audio/MIDI. But what about when the song is done and you need to release it? That is when the Project view comes into play. Start by opening Studio One and making a new session. Except this time instead of clicking "Record and Mix" click on "Master and Release" to open the Project page. Here you can drag ang drop Mixdowns into the timeline at the bottom of the screen. If your have a .song file from a previous mix you can also load that here instead of the /mp3 or .wav. This is useful because if you make any changes to the mix, they will update in the master without you having to re-export a new file.

Notice that the timeline at the bottom is set for 80 minutes by default. This is because the length of a standard audio CD is 80 minutes. So if yous Mastering session fits on the timeline it can all be burned to a single audio CD if desired. You can see how close to full you are with the bar on the top of the window. In the top left of the screen you will see information for whichever track you select from the timeline. Clicking the small arrow next to the track name will open a dropdown menu to adjust the metadata about the track. In between the track information panel and the CD fill % are the export options. We will discuss that later.

In the middle of the screen is where information about the song will display. This is mainly loudness information. The large window in the middle of the screen will function as the Loudness Meter plug-in, showing the volume of various frequency bands. The display of this information can be adjusted per your preferences. An instance of the Phase MEter plugin is also available here as well.

## Basic Audio Mastering Concepts

So what is Audio Mastering?

Generally it is used to set the loudness of a track so that it can be easily heard and a few small adjustments to make an album or EP flow better and sound as good as possible on the final playback medium.

For more information on Audio Mastering, check out this video interview:

!?[sound-on-sound-mastering-video](https://www.youtube.com/watch?v=fx8XQcHnSDY)

### Adjusting Loudness

One important aspect of Mastering is loudness and the loudness wars. As audio technology continued to evolved, audio was able to be played back at louder volumes. When audio became digital, this ceiling was greatly increased. During this time, many songs were made louder and louder, which didn't do anything to help improve the quality of the music and made it difficult to play multiple songs in a row without having to adjust the volume between each one. To help combat this, many streaming platforms implements an average loudness cap and will forcefully limit any tracks that exceed this.

In the Studio One Project page, you can easily see the loudness information for your selected track. We will be focusing on the LUFS value in this unit. LUFS is a measurement that represents the average volume of the audio track. it stands for Loudness Unit Full Scale. Most places that you submit your final master to will have loudness rules about what can be submitted. This means that any audio submitted to places like Spotify, Apple Music or Youtube that don't meet their loudness guidelines will have their volume altered so that they meet the compliance. This, as you might expect, distorts the original mix, resulting in an inaccurate representation fo th emusic. How can you fix this? Master to the appropriate level to begin with!

Most sites will have the information published, but Studio One actually has built in protection which we will get to when we discuss exporting.

To check the LUFS value for your track, select the track and click "Loudness Information" the value may have to update, but when ready the LUFS will appear in a drop down. You can adjust the loudness of your track until it meets the requirements for your desired platforms. To do this, I recommend utilizing the Studio One Limiter so you can boost the gain to the needed level without forming the track to clip.

!?[lufs-explained](https://www.youtube.com/watch?v=myTcnK1lRUA)

### Effects and Adjustments

When mastering your audio, you have one final chance to make any large-scale adjustments or add effects. In most cases, you would make any large changes in the song's mix. However, when putting together an album or an EP, a few common processes can happen.

* Compression: having a little compression on each track (the same compression) can help keep everything at the same relative level and have the EP flow better. Basically, like potentially putting everything in the same reverb, it helps everything feel like it belongs in the same space.
* Stereo effects: sometimes stereo widening can happen in the mastering phase. This won't effect the content of the song, but can help to give everything a little more space in the mix so everything can be heard.
* EQ: Small eq changes can also be made in the mastering stage. If a song as a whole has a lot of low end rumble, sibilance, or some other problematic frequency, small-scale boosts and cuts can help tame those and make each song better match the others in the album.

This is a short list of potential effects use din mastering. These video goes over a few more in a little more detail. 

!?[mastering-what-why](https://www.youtube.com/watch?v=x0ce05iAdxI) !?[s1-mastering](https://www.youtube.com/watch?v=qCfiWJkXchM) !?[some-plugins](https://www.youtube.com/watch?v=NdH1sIRzP0o) 

## Exporting Your Project for Release

When you are completely done with mastering, You will need to export the file that you can share with others!

First save your project, then look at the toolbar at the top of the screen. Many of these you can ignore for this class, but we will focus on two: Burn and Digital Release.

If you have a physical CD that you would like to burn your track to, you can select the burn option. This will open a dialog box where you can select th settings, similar to exporting the mixdown, as well as the specific CD drive to burn the disc. You will need to have a drive installed on your computer, and a blank CD in that drive in order to export this way. 

![digital-export-window](content\media\exportProj.png)

Most of the time however, you will be exporting to a digital release. This will create an audio file and save it to your computer instead of burning it to a CD. The process for this is extremely similar ot exporting a mixdown, but with a few unique options:

* Tracks: If you have multiple tracks in your project, you can choose which ones to export. This way you can export a whole album at once to save time.
* Loudness: Studio One will automatically adjust the loudness of your mastered files to match the specifics of a common streaming platform. You can select forma variety of options and presets, and have Studio One automatically lower any problematic volume levels. 

While the loudness adjustments in Studio One is less problematic than some of the ones used by streaming platforms, it can still distort mixes, so the best practice it to utilize this along with the manual volume adjustment so only a minimal amount of small changes are made.

Check out this video and the [Studio One 6 manual](https://s1manual.presonus.com/Content/Mastering_Topics/Publishing_Your_Project.htm) for more information about adjusting loudness and exporting your final project from the project page!

!?[target-loudness-video](https://www.youtube.com/watch?v=yn6PzVpJQN0)

### Test Your Knowledge!

True or False: You can use any audio you find in any music you make with no drawback or potential legal repercussions.

- [[ ]] True
- [[X]] False

True or False: The Mastering Artist should focus on making a mix work on the performance platform, not making large changes to improve the quality of the original mix.

- [[X]] True
- [[ ]] False