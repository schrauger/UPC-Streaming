# UPC-Streaming

# Setup

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
* `C:\Users\UPC\Desktop\Quotes - Change these every week`
* Do not add line breaks to the quote unless the quote calls for it. The text will automatically reflow and resize to fit, so line breaks are only needed if a quote uses them for artistic or other purposes (like a poem or psalm).


## YouTube 
* Go to your Video Library and to the Live section to Create a Go Live stream.
* https://studio.youtube.com/channel/UClsIo25a477hwJqr0tbCGFw/livestreaming/manage

* Copy the previous week's settings.
  * update the title.
  * Set the date to today (or the upcoming sunday) and the time to **5 minutes prior to** the sunday morning service time - 9:55am
    * This is so the stream starts 5 minutes early and shows the pre-service announcements, Reflection quote, and gives the visual ambiance of people arriving to church.
* Click create
* Click on your newly scheduled livestream (click on the thumbnail) to go to the livestream setup
* Make sure the stream key is set to "1 Primary Worship Broadcast (1080)"

## Facebook

* Go to this url:
* https://www.facebook.com/live/producer

* Under `Choose where to post`, choose `Post in group` -> `UPC Orlando`
* Select the radio button `Schedule live video event`
* Click <kbd>Next</kbd>

* Set the date to today (or the upcoming sunday) and the time to **5 minutes prior to** the sunday morning service time - 9:55am
  * This is so the stream starts 5 minutes early and shows the pre-service announcements, Reflection quote, and gives the visual ambiance of people arriving to church.

* Set the title (update the date)
<pre>
UPC Worship Service <b>2021-08-15</b>
</pre>

* Set the description (same for every video)
<pre>
Welcome!

Worship Guide: https://www.upcorlando.org/weekly-worship-guides
</pre>

* Under `Setup Options`, ensure the toggle is enabled for `Use a Persistent Stream Key`.
* Under `Setup Options`, enable the toggle for `Use a Backup Stream`.

Ensure all the settings are correct, then click <kbd>Schedule Live Video</kbd>

## Castr.io 
* https://castr.io
* Make sure Facebook and YouTube are ready with a **scheduled** stream before enabling castr.
* Go to [dashboard](https://castr.io/app/dashboard), click on the UPC Worship Service stream.
* Click the toggle to go live on all streams. 
  * This will not cause Facebook or YouTube to go live but will still let you test both platforms to ensure you are receiving video streams.


# Service

## 45 minutes before
### OBS
* Set scene to `! Prelude (if band/piano player)` - don't forget to <kbd>transition</kbd>
* Start broadcasting to castr.io, and activate the toggles within castr to push the stream to youtube and facebook (or just click Toggle All)


## 5-15 minutes before
* Start Recording on the Canon Camera (physical record button, to save a backup to the internal sd card)
* As long as all is good, click the Go Live button on the Facebook page and on the Youtube page
* Have one of the cameras zoomed out to view the congregation (preset 0), or zoomed in on the current prelude band member(s)

## During service
* When the timer hits 0 and the projector starts playing the Intro video:
  * **OBS** - Switch to `! Intro Part 2 - switch to this scene while intro video plays`
* After the video fades away and the service starts:
  * **OBS** - Switch to `! Main Service w/slides - MAIN SCENE DURING SERVICE` for all songs and for the sermon
  * If any photos or videos are to be shown during announcements, switch to the `Main Service w/videos & slides` scene

## After service
* After the doxology, the band will play a song. Change OBS to `! Postlude`, and have the camera set to a wide view of the auditorium.
* When the band finishes playing, click the Stop button in OBS to stop streaming to castr.

* In castr.io, toggle off for all platforms.
* In Facebook and Youtube, end the stream.
* On the Canon camera, press the record button to stop the internal recording.
* Turn off the Canon camera.
* Close all programs and shut down the computer.

