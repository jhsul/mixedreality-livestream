# Live video streaming in mixed reality

This repo contains a Unity application for live streaming video to a mixed reality headset (tested with the Hololens 1). The video feed is HLS/DASH and comes from a raspberry pi/USB webcam running [this script](https://github.com/cdgriffith/pi_streaming_setup). Since there is a noticeable ~20sec video delay, this project will probably be replaced by a WebXR application so that we can take advantage of the browser's WebRTC API for faster video streaming.

<p align="center">
    <img src="demo.gif">
</p>

### Requirements

- Unity
- [AVPro Unity Package](https://renderheads.com/products/avpro-video/) (I used the trial version)
- HLS/DASH video stream with a public IP and `manifest.mpd` file
