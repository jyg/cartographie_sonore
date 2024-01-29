# helloworld.io
testing puredata on web (pd4web https://github.com/charlesneimog/pd4web)

visit site here https://jyg.github.io/helloworld.io/

## Current status
Those are attempts to add a gui using 2 differents frameworks
* NexusUI.js
* P5.js

Transmitting values to pd4web from p5.js cannot be done from draw() loop, but can be done from inside following functions, using sendToPureData()  :
* mousePressed()
* mouseDragged()
* mouseMoved()
