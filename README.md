Simple MP3 decoder/player for Node.js

Split into two parts, the `fs-decoder.js` that writes a PCM stream to `stdout`, and the `pcm-speaker.js` that reads a PCM stream from `stdin` and plays the audio.

Usage:

`node fs-decoder.js <path/to/an/mp3/file> | node pcm-speaker.js`
