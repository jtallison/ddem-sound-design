# Unit 7: Video Workflow in Studio One 6

This unit is all about using a video file with Studio One 6. You cannot do edits like in Adobe Premiere, but You can easily import a video to create your own sounds for, and export everything as a single file. We will also discuss the practices of Foley sounds and creating soundtracks in a few lab projects.

 

## Adding Videos to Your Project

Studio One 6 Professional is able to work with video files as well as audio files. It is important to know that versions other than Professional are unable to work with video files, so you will need to utilize other softwares for this if that is the version you have. It is also important to remember that Studio One 6 is a Digital AUDIO Workstation. It has no video editing capabilities, and solely works with video as a way to add your own sounds to a pre-existing video file.

To load a video in Studio One 6, simply drag and drop it into a Studio One session from the file browser. The video will then appear in the video player. If you have access to two monitors, I recommend putting the Studio One window on one and the video on the other, as the video player can cover a lot of the session screen. If you close the video player, you can open it again by clicking the video tape icon, or View > Video Player.

Once loaded, the video track will appear above your audio tracks, and display both the video and the audio. You can mute the original video audio by muting either the track, or clicking the mute button on the video player. You are able to trim and slice the video file just like any other event so if you have a larger original file, you can arrange it to just the scenes you need and the order you need them. This is the extent of the video editing capabilities of Studio One 6.

Once you have mixed and arranged your audio as you would like, you can export a new video file with your audio included! To do this, click on Song > Export Video. In the popup window you can choose where the file saves and its name, as well as the file type. Under Export Range you must specify the parts that you want to export, just like when creating a mixdown. You can have it match the duration of the source file which is useful if you have not clipped and deleted scenes. If that is the case, you can utilize the loop bar or markers to set the durations. Once exported, the result is a video file that will play your audio along with the source video!

Check out the [online manual for more information about working with video in Studio One 6!](https://s1manual.presonus.com/StudioOneReferenceManual.htm#Video_Playback_and_Sync_Topics/Chapter-Video_Playback_and_Sync.htm?TocPath=Video%2520Playback%2520and%2520Sync%257C_____0).

## Foley Sounds

Foley is the art of adding realistic sounds to movies, tv, and radio. It was originally pioneered by Jack Foley in the 1920’s, the practice sought to bring a level of realness to the entertainment experience. In modern film and television, microphones are focused on getting the actor's dialogue, and are located far away from the sound source so as to remain off-screen. This means that many sounds in the scene are either ignored, removed, or otherwise not recorded. This can be problematic when wanting to create a realistic scene as there are more sounds than just dialogue in the real world. To offset this silence, Foley Artists will build up the environmental sounds of a film in order to create the desired environment.

Generally Foley artists will work by seeing what sound they have to recreate. This could be anything; if it is in the scene, it is fair game. Then they have to plan out how to make those sounds, and record them in sync with the recorded video. A simple example would be to record footsteps. A foley artist would find similar shoes and a surface to walk on in order to create the sound you would expect from the video, then record themselves walking in time with that video to create the footsteps. A mixing engineer would then balance the various recordings and layers of sound to create the final effect. 

Here are a few interviews/documentaries with Foley Artists about what they do and how they do it:

!?[foley-video-1](https://www.youtube.com/watch?v=UO3N_PRIgX0) !?[foley-video-footsteps](https://www.youtube.com/watch?v=QBDU3pJaU6c) !?[foley-video-horror](https://www.youtube.com/watch?v=1BQvCCB-PiA)

## Audio Soundtracks

## Exporting Video Files

Once you have completed your work, you could export the mixdown and attach it to he original video in a video editing software. However, Studio One 6 Professional can actually do this automatically and save you time in completing the larger video project. This is basically the only video editing possible in Studio One 6, so it is recommended to have the completed video, and then add the sounds to export a final product.

To export a video file, you must first have a source video imported into the video track. See the lesson on adding videos to your project if needed. When done, click Song>Export Video in the main tool bar at the top of the screen. Using the window that pops up you can set the file name and save location just like exporting a Mixdown file. The remaining options are similar to exporting a mixdown, but with a unique flair for working with video. 

Using the MPEG-4 Video format will allow you to have the most compatible and highest resolution video possible while keeping the file size manageable. You can change the codecs for video and audio if desired, but leaving them as the default H.264 and MP3 will work for basically all use-cases. When it comes to determining the amount of content to export, the first two options are the most useful. You can use the loop bar to set the export region manually like when exporting Mixdowns, or have Studio One automatically export for the duration of the video. Other than that, make sure you are exporting the Main channel output and you are ready to hit OK.

Because the computer is creating an audio file, attacking it to the video (in sync) and then writing the new video file, expect that your video exports will take longer than an audio export. Be sure to plan accordingly so that your files are finished by the end of class!


## Lab 7

Lab Objectives:

* Importing Video files into Studio One 6 Professional
* Lining up audio and Video elements
* Basics of Foley Sound Creation

Instructions:

There are two sets of instructions for this lab: One for if you have Studio One 6 Professional, and one for if your DAW does not have native video support. Follow the instructions that are appropriate for your class.

Instructions for Studio One 6 Professional:

1. Begin by finding a video file to use for this project. You are certainly welcome to supply your own video for this project, including one you shoot and edit yourself. If you need to find one online, your best sources are likely Archive.org and YouTube.
    * With Archive.org, video files from various categories are freely available to download. Many of them are in the Public Domain, meaning that their “exclusive intellectual property rights have expired, have been forfeited, have been expressly waived, or are inapplicable.” However, due to the times in which some of these older films were produced, some of them may contain offensive content. Please be sensitive to this matter if you are looking for videos on Archive.org. When downloading, simply choose the best quality file available to you.
    * Many videos on YouTube are likely subject to copyright claims. We will be using these videos for educational purposes under the Fair Use doctrine. Your video projects will only be shown in class, only stored locally, and deleted from the lab after the projects have been graded. Students will assume all legal responsibilities if they decide to distribute these videos elsewhere. Use a YouTube downloader site to download videos from YouTube - you should be able to find one easily through an online search.
2. Once you have your video file, drag and drop it into Studio One 6 and use the Arrow tool to trim the video event to a single scene. The trimmed portion should not exceed 100 seconds, and should begin immediately when playback starts.
3. Mute any audio present in the original clip.
4. Utilizing both the audio clips from Lab 3 as well as a handful of new audio recordings from freesound.com or archive.org, create Foley sounds for the main events in your scene. Be sure to include things such as footsteps, weather, environmental sounds, etc. If it is happening on the screen, you should be able to hear it.

_Optional: utilize panning and volume automation to have the sound files match their movement on the screen._

5. When you are finished, export the video as instructed in “Mixdown Requirements” and submit it to your teacher.
6. As always, save a backup copy on your personal storage media. This can be a flash drive, SD card, or online cloud storage. Be sure to backup both the session AND the exported video.

Instructions for using a DAW other than Studio One 6:

1. Begin by finding a video file to use for this project. You are certainly welcome to supply your own video for this project, including one you shoot and edit yourself. If you need to find one online, your best sources are likely Archive.org and YouTube.
    * With Archive.org, video files from various categories are freely available to download. Many of them are in the Public Domain, meaning that their “exclusive intellectual property rights have expired, have been forfeited, have been expressly waived, or are inapplicable.” However, due to the times in which some of these older films were produced, some of them may contain offensive content. Please be sensitive to this matter if you are looking for videos on Archive.org. When downloading, simply choose the best quality file available to you.
    * Many videos on YouTube are likely subject to copyright claims. We will be using these videos for educational purposes under the Fair Use doctrine. Your video projects will only be shown in class, only stored locally, and deleted from the lab after the projects have been graded. Students will assume all legal responsibilities if they decide to distribute these videos elsewhere. Use a YouTube downloader site to download videos from YouTube - you should be able to find one easily through an online search.
2. Once you have your video you will need to utilize a separate software in order to trim the video to a specific scene of your choice. This scene should be no longer than 100 seconds, and should begin immediately when playback starts. There are a few options for this. Each video software has its own unique way of working, so be sure to check out its relevant reference materials. There are other softwares available as well, so utilize the one that works best for you!
3. If using a Mac, iMovie is one of the quick, free options. The trimming method is the same as in Studio One. Below are a few other options for editing videos. All of the below options are available regardless of your operating system
    * Adobe Premiere (Mac and Windows)
    * Davinci Resolve (Mac and Windows)
    * [wevideo.com](https://www.wevideo.com)
4. Once trimmed, watch through your clip at least 5 times. Be sure to note when specific events are happening such as footsteps, weather, etc. If it could potentially be heard in the scene, make a note of it and the specific second it happens at.
5. In your DAW, Use your list of sound events to place sound clips at the right place. You can utilize both the audio clips from Lab 3 as well as a handful of new audio recordings from freesound or archive.org.
6. When done, export the audio as a .wav or .mp3 file and import it into the video project.
7. Line up the audio and video. If your timings were good, then everything should fall easily into place with minimal adjustments.
8. Mute the original audio from your video (if present) and follow the instructions for your video software to export a .mp4 file with your sounds attached to the video. Try and follow the “Mixdown Requirements” as much as possible.
9. As always, save a backup copy on your personal storage media. This can be a flash drive, SD card, or online cloud storage. Be sure to backup both the session AND the exported video.

Mixdown requirements:

* File name: YourFirstNameYourLastName-Lab7.
* Format: MPEG-4 Video
* Video Codec H.264
* Audio codec: AAC (if available), WAV, or MP3 (if no other options ara available.)
* Make sure to export the Main output.
* Be sure that the duration of the resulting audio file matches what you expect. Your Lab project should be between approximately 60 and 100 seconds in duration.
* Be sure to follow your teacher’s guidelines for file submission.

 