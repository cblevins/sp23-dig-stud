---
title: Introduction to Adobe Premiere Pro
---

Today you will be learning the basics of Adobe Premiere Pro.

## Overview of Adobe Premiere Pro

This video provides a short overview of what Adobe Premiere Pro is and how you might use it:

{% include video id="QlU6mFMc3kc" provider="youtube" %}h

## Making Your First Video

To start to get familiar with Adboe Premiere Pro, you're going to be making a short video featuring some turtles.

### Start a New Project

- Download the following .zip file into your `video-editing` folder by right-clicking on the link and selecting Save as (or save target as): [premiere-videos.zip]({{site.baseurl}}/modules/premiere-videos.zip). 
- Extract the contents of the .zip file ([Windows instructions](https://support.microsoft.com/en-us/windows/zip-and-unzip-files-f6dde0a7-0fec-8294-e1d3-703ed85e7ebc#:~:text=Open%20File%20Explorer%20and%20find,folder%20to%20a%20new%20location.), [Mac instructions](https://support.apple.com/guide/mac-help/zip-and-unzip-files-and-folders-on-mac-mchlp2528/mac#:~:text=unzip%20(expand)%20a%20compressed%20item)).
- The extracted .zip folder has four files:
  - duck-and-cover-intro.mp4
  - tmnj.gif
  - led-zepplin.mp3 
  - turtle-walking.mp4
- On your computer, create a new folder inside your `tutorials` folder named: `video-editing`.
- Open Adobe Premiere Pro and start a new project. 
- Name the project `intro-premiere.prproj` 
- Make sure the Project location is inside your `video-editing` folder.
- On the right hand panel, de-select `Create new sequence` (so it's not checked)
- Click the blue `Create` button.

### Get Oriented

- Adobe Premiere's interface is organized into `Panels` of different features.
- There might be a lot of panels open by default when you open the app, but we don't need all of them since we're going to be only doing some basic things today. 
- Go to `Window` -> `Workspaces` -> `Learning` - this reduces the number of available windows and tools.
- This will give you just a few panels (they should be empty right now):
	- `Project`: an overview of the different pieces of media (video, sound, images, etc.) that make up your full video - your "raw material" you're going to use to build the full video
	- `Source`: Use this to preview individual media files (video, sound, etc.) to see what they look/sound like.
	- `Timeline`: This panel is where you will splice together, edit, and overlay different pieces of media 
	- `Program`: Where you can see and hear the combined media pieces - ie. your full video.

### Import and Preview Your Media Files
- Click the `Import` tab at the very top left. This brings you back to a screen you were just on when you created a new project.
- Use the left-hand panel that says `Local` with some folders on it to navigate to the folder you downloaded earlier: `premiere-videos`. When you've found the folder and clicked on it, you should see four thumbnails corresponding to your four files.
- Select the `duck-and-cover-intro` thumbnail by clicking once on it, then click the blue `Import` button at the bottom right.
- Look at the `Project` panel Double-click each of the thumbnails of files in the `Project` panel to load it into the Source Monitor Panel and get a preview of what it contains:
- Repeat the above steps to import:
  - tmnj.gif
  - led-zepplin.mp3 
  - turtle-walking.mp4
- Note: You can import multiple files at once by clicking on each of them before clicking the `Import` button.
- Preview each of your four media files by clicking on the thumbnails in the `Project` panel and dragging them onto the `Source` panel. Then click the play button to see/hear them.
  
### Add Clips To Your Timeline
- The `Timeline` panel is where you're going to splice and layer together all of your media clips
- Click and drag the `duck-and-cover-intro` video clip in the `Project` panel onto your `Timeline`. 
- This creates a new "sequence" in your timeline named `duck-and-cover-intro` should see a long colored ribbon on the timeline with a small thumbnail of the video on it. 
- Your `Program` panel should also be showing the video you just added. Click the play button on the `Program` panel and notice that a vertical bar advances along the `Timeline` panel as it plays.
- Click and drag the `turtle-walking.mp4` clip onto the timeline and release it to the *right* (immediately after) the end of your Duck and Cover video clip. 
- Click and drag the `tmnj.gif` clip onto the timeline and release it *above* the `turtle-walking` clip, so that it appears "on top of" the ribbon roughly roughly halfway (in the middle) of the `turtle-walking` clip.
- Click and drag the `led-zepplin.mp3` clip onto timeline and release it immediately to the *right* of your `duck-and-cover-intro` clip and directly *under* the `turtle-walking` clip.
- Use the blue upside-down arrow at the top of the timeline to rapidly "scrub" through your timeline.
- Zoom in or out on your timeline using the two dots at the bottom of the timeline (this is helpful if you have clips with much different lengths - ie. one very short and one long clip).
- The `Program` field should have a video that looks something like:
	- Extended footage of old film with a turtle
	- Immediately followed by video of a turtle walking with Led Zepplin music playing in the background
	- Somewhere in the middle of the turtle walking it should briefly cut to a clip of the Teenage Mutant Ninja Turtles before going back to the video of the turtle walking.

### Trim and Rearrange Clips
- Let's make the clips shorter so the final runtime is closer to 35-40 seconds.
- Our **first trim** is going to shorten the video of the turtle walking (`turtle-walking`) so that the end of the clip lines up with the end of the audio clip of the Led Zepplin song (`led-zepplin`):
	- Hover your mouse over the right edge (the end) of the `turtle-walking` clip until it turns into a red bracket icon with an arrow pointing to the left. 
	- Click and drag the new icon to the left until it "snaps" to align with the right edge of the audio track `led-zepplin` underneath it.
- Our **second trim** is going to cut the first video clip `duck-and-cover-intro` down to around 20 seconds so that it transitions to next clip right around when the dynamite explodes:
	- Instead of dragging the edge of the clip like we did in the first trim, we're going to use the `Ripple Edit Tool` - this makes sure that there isn't a gap between clips.
	- Click the `Ripple Edit Tool` in the narrow tool panel immediately to the left of the timeline (hover over each icon to see its name). It is one vertical bar with two arrows pointing out from it. 
	- Hover your mouse over the right edge of the `duck-and-cover-intro` clip on the timeline so that it turns into a yellow bracket with a left-hand arrow. 
	- Drag the new icon to the left until you get to the 20-second mark (when the dynamite explodes).
- Our **third trim** is going to cut the two seconds of black screen at the *beginning* of the `duck-and-cover-intro` clip:
	- Click the `Selection Tool` on the toolbar above the `Ripple Edit Tool`
	- Hover over the very beginning of the `duck-and-cover-intro` clip until your mouse turns into a red bracket with an arrow
	- Click and drag to the right on the clip while watching the `Program` panel until you see the clip transition from a mostly black screen to the turtle first appearing and then let go of your mouse (roughly 2 seconds). 
	- Notice that this has trimmed off the beginning of the clip, but that this leaves a gap on our timeline.
	- To fix the gap, make sure you have the `Selection Tool` clicked and then click and drag the white box over *all* of your video and audio clips in the timeline so that they're all selected (each of them should now have a white box around them)
	- Click inside any of the clips on the timeline and then drag to the left until it "snaps" and aligns with the very beginning of the timeline.
- [Tutorial video if you get stuck](https://helpx.adobe.com/premiere-pro/how-to/trim-video-clips.html)

### Export Your New Video 

- Export your project content as a single new video file named `my-first-video.mp4`
- Go to `File` -> `Export` -> `Media` 
- Change the File Name to `my-first-video` 
- Make sure the Location is set to `video-editing` folder on your computer 
- Set the Preset to: `March Source - Adaptive Medium Bitrate`
- Set the Format to `H.264` 
- Click the blue `Export` button
- Go into your `video-editing` folder on your computer and make sure you have a new file named `my-first-video.mp4`. Try opening it and watch your amazing new video!

## Helpful Tutorials
- [Create a project and import media](https://helpx.adobe.com/premiere-pro/how-to/create-project-import-media.html)
- [Explore Premiere Pro panels](https://helpx.adobe.com/premiere-pro/how-to/work-explore-panels.html)
- [Adding clips and creating sequences](https://helpx.adobe.com/premiere-pro/how-to/create-edit-sequence.html)
- [Trimming clips](https://helpx.adobe.com/premiere-pro/how-to/trim-video-clips.html)