# Recording Audio and Video With JavaScript

Learn how to record audio and video with JavaScript with using the 
[MediaStream Recording API](https://developer.mozilla.org/docs/Web/API/MediaStream_Recording_API).

There is not an elaborate setup for this repository since it is only a frontend application. We will have more improvements to this code shortly, including how to save the video to a server.

## Developer Getting Started

Run the following commands in your terminal to prepare for coding.

```commandline
mkdir record_audio_and_video_with_javascript
cd record_audio_and_video_with_javascript
touch index.html style.css
```

I did not put the JavaScript code into its own `.js` file for easier readability. I did put the `css` code into its own file in order to not add clutter to the `index.html` file.

## Process

Open `index.html` in your web browser. The following command is useful for macOS.

```commandline
open index.html
```

- You will be asked to allow access to the camera and microphone, so click the "Start Camera" button.
- Click the "Allow" button.
- Click the "Start Recording" button to start recording.
- Click the "Stop Recording" button to stop recording.
- Click the "Download Video" link to download the recorded video and play it back.

