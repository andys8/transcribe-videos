# Transcribe Videos with Node.js

This is a barebones project which transcribes either local or remote video files with [Deepgram](http://deepgram.com)'s AI Speech Recognition API.

## Setup

```
git clone https://github.com/deepgram-devs/transcribe-videos.git
cd transcribe-videos
npm install
```

## Usage

Uncomment either the `transcribeLocalVideo()` or `transcribeRemoveVideo()` calls at the top of `index.js` and run with:

```
node index.js
```