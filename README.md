# loistoSYNC
A/V Sync application for streaming

![1](https://github.com/reaby/loistoSYNC/raw/main/resources/loistosync.png)

You'll need some external video editor to see the audio and video frame at that time.
Idea is to match the the audio peak with the 0-point red background rectangle.
Your reference is always audio. So go to the audio peak, and see the value of video.
Adjust your OBS sync offset accordingly and take another test, repeat until your audio peak matches the 0-point rectangle.

## App Usage
1. Select framerate.
2. Click anywhere at the page to start polling, click again to stop.

:warning: Output sound is set loud (Sound output peaks to 
0.1dBfs)... if you test on laptop/pc whatever please lower your headphones volume before testing. The app is optimized for cellphone/pad usage, thus the sample needs to be loud.
