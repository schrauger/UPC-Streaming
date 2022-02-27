# UPC-Streaming

# Setup

## Quick Links
* Instructions - [https://github.com/schrauger/UPC-Streaming#readme](https://github.com/schrauger/UPC-Streaming#readme)
* Planning Center - https://services.planningcenteronline.com/dashboard/0
* Castr.io Dashboard - [https://castr.io/app/multistreams/5f7610a85f9db667efaad707/dashboard](https://castr.io/app/multistreams/5f7610a85f9db667efaad707/dashboard)
* Facebook Livestream - [https://www.facebook.com/live/producer](https://www.facebook.com/live/producer)
* Youtube Livestream - [https://studio.youtube.com/channel/UClsIo25a477hwJqr0tbCGFw/livestreaming/manage](https://studio.youtube.com/channel/UClsIo25a477hwJqr0tbCGFw/livestreaming/manage)
* Web Captioner - [https://webcaptioner.com/captioner](https://webcaptioner.com/captioner)

## Hardware 
* Turn on Canon backup camera
* Boot up streaming computer (congratulations, by reading this note, you have successfully completed this step!)
* Open OBS Studio, SNAZ, and Chrome

## ATEM Mini Pro (HDMI camera switcher) 
Make sure the Audio button for MIC 1 is On - it should be red. If the white Off button is lit, press the On button. This is required to have sound board audio come through to the stream.

## SNAZ 
* The text line changer and countdown should automatically start. But if they're incorrect or aren't running, go through these steps to enable them:

### `Text Line Changer` tab 
* Click start

### `Time, date and countdown` tab
* Within the `Countdown to specific time` section
  * Set the date to today, and the time to the service start time (10:00am)
  * Click start

## OBS Studio 

* Change the Quote and Author text files located in this folder:
* `C:\Users\UPC Streaming\Desktop\Quotes - Change these every week`
* Do not add line breaks to the quote unless the quote calls for it. The text will automatically reflow and resize to fit, so line breaks are only needed if a quote uses them for artistic or other purposes (like a poem or psalm).


## YouTube 
* Go to your Video Library and to the Live section. Click the <kbd>SCHEDULE STREAM</kbd> button to Create a Go Live stream.
* https://studio.youtube.com/channel/UClsIo25a477hwJqr0tbCGFw/livestreaming/manage

* Copy the previous week's settings by clicking the <kbd>REUSE SETTINGS</kbd> button
  * Update the title with this weeks speaker, the sermon <b>series</b>, and the date
  * Update the description, changing the current sermon <b>title</b>, and removing the timestamp bookmarks
  * Set the date to today (or the upcoming sunday) and the time to **5 minutes prior to** the sunday morning service time - 9:55am
    * This is so the stream starts 5 minutes early and shows the pre-service announcements, Reflection quote, and gives the visual ambiance of people arriving to church.
* Click create
* Click on your newly scheduled livestream (click on the thumbnail) to go to the livestream setup
* Make sure the stream key is set to "1 Primary Worship Broadcast (1080)"

## Facebook

* Go to this url:
* https://www.facebook.com/live/producer/v2/?target_id=2391252443

* On the left, under `Choose where to post`, choose `Post in group` -> `UPC Orlando`
* In the `Create live video event` section, click the <kbd>Select</kbd> button
* Click the `Fill in with past event details` toggle, to copy the previous event settings and info
* Set the date to today (or the upcoming sunday) and the time to **5 minutes prior to** the sunday morning service time - 9:55am
  * This is so the stream starts 5 minutes early and shows the pre-service announcements, Reflection quote, and gives the visual ambiance of people arriving to church.

* Set the title (copy from YouTube)
* Set the description (copy from YouTube)
* Click <kbd>Next</kbd>


* Click on the `Settings` section, and click `Stream`
* Under `Setup Options`, ensure the toggle is enabled for `Use a Persistent Stream Key`.
* Under `Setup Options`, enable the toggle for `Use a Backup Stream`.

Ensure all the settings are correct, then click <kbd>Create event</kbd>

* Click <kbd>Setup live video</kbd> to view the video preview and livestream controls
* You <b>MUST</b> also click on the <kbd>Streaming software</kbd> button to switch to the livestream software video source instead of the selfie camera

# Service

## 30 minutes before
### OBS
* Set scene to `! Prelude (if band/piano player)` - don't forget to <kbd>transition</kbd>
* Click <kbd>Start Streaming</kbd> under the main `Controls` section, which will start sending data to YouTube
* Click `Start` under `Facebook Primary`, which will start sending data to Facebook

## 5-15 minutes before
* Start Recording on the Canon Camera (physical record button, to save a backup to the internal sd card)
* As long as all is good, click the Go Live button on the Facebook page and on the Youtube page
* Have one of the cameras zoomed out to view the congregation (preset 0), or zoomed in on the current prelude band member(s)

## During service
* When the timer hits 0 and the projector starts playing the Intro video:
  * **OBS** - Switch to `! Intro Part 2 - switch to this scene while intro video plays`
* After the video fades away and the service starts:
  * **OBS** - Switch to `! Main Service w/slides - MAIN SCENE DURING SERVICE` for all songs and for the sermon
  * If any photos or videos are to be shown during announcements, switch to the `Main Service, 50/50 split screen with direct projector - Open OBS on ProPresenter Mac for NDI Output` scene
    * Make sure to tell the ProPresenter operator to open OBS Studio on their computer. It does not have to run or have anything happen besides being open 

## After service
* After the doxology, the band will play a song. Change OBS to `! Postlude`, and have the camera set to a wide view of the auditorium.
* When the band finishes playing, click the Stop button in OBS to stop streaming to castr.

* In castr.io, toggle off for all platforms.
* In Facebook and Youtube, end the stream.
* On the Canon camera, press the record button to stop the internal recording.
* Turn off the Canon camera.
* Close all programs and shut down the computer.

