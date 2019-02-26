#launchpad-mini-browser
This is a browser port from https://www.npmjs.com/package/launchpad-mini
Usage is the same, but no disconnect function.
```
const pad = new Launchpad();
await pad.connect();
```
You may have to allow the webpage to access midi-devices.

I do not own this code! I only ported it to be used in browsers.