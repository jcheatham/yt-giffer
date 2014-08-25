# Youtube GIFfer

Youtube GIFfer is a javascript bookmarklet shim to assist in creating animated GIFs from youtube videos directly in the browser.

## Setup

Create a [bookmarklet](http://en.wikipedia.org/wiki/Bookmarklet) pointing to:

```
javascript:(function(){var s=document.createElement('script');s.setAttribute('src','https://rawgit.com/jcheatham/yt-giffer/master/yt-giffer.js?t='+Date.now());document.getElementsByTagName('head')[0].appendChild(s);})();
```

## Usage

![Screenshot](https://raw.githubusercontent.com/jcheatham/yt-giffer/master/screenshot.png)

 1. Open up a youtube video.
 2. Click the bookmarklet.
 3. Capture some frames (set some parameters, whatever).
 4. Compile.
 5. Save.

## ToDo

In no particular order.

 * Use a Worker.
 * Configurable loop count, per-frame durations.
 * imgur upload.

## Contributions

Are welcome via pull request.  Or fork it and go crazy.
This was only tested on the latest Chrome as a weekend hack, no idea if it works on anything else.

## Thanks

Biggest thanks possible go to https://github.com/antimatter15/jsgif without which this likely would never have gotten off the ground.

Various other links that were useful (in no particular order of course):
 * http://appcropolis.com/blog/web-technology/using-html5-canvas-to-capture-frames-from-a-video/
 * http://stackoverflow.com/questions/4298084/html5-frame-by-frame-viewing-frame-seeking
 * http://stackoverflow.com/questions/10136232/using-javascript-jquery-to-access-picture-content-for-a-frame-in-a-video
 * http://techslides.com/demos/video/generate-animatedgif.html
 * http://jsfiddle.net/usernamedemanded/893aM/37/
 * http://www.w3.org/2010/05/video/mediaevents.html

## License

[MIT Licensed](https://github.com/jcheatham/yt-giffer/blob/master/LICENSE)

