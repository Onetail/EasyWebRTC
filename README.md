WebRTC Video Sever
==================

An easy WebRTC video server which enable users to 

- 1-to-1 video chat
- Pure WebRTC; no external libraries
- Works in current versions of Firefox and Chrome

### Usage

The signaling server uses Node.js and `ws` and can be started as such:

```
$ npm install ws
$ node server/server.js
```

With the client running, open `client/index.html` in a recent version of either  Chrome or Firefox.

Note that if using Chrome and opening the file locally, you must run Chrome with the `--allow-file-access-from-files` flag. Or you could serve the files with a webserver (Python's SimpleHTTPServer is a good option).

### Reference
- https://developer.mozilla.org/en-US/docs/Web/Guide/API/WebRTC
- https://shanetully.com/2014/09/a-dead-simple-webrtc-example/