# cartographie sonore
Projet de cartographie sonore internet
propulsée par 
* pd4web https://github.com/charlesneimog/pd4web
* p5.js https://p5js.org/

démo en ligne ici https://jyg.github.io/cartographie_sonore/

## Current status
Those are attempts to add a gui using 2 differents frameworks
* NexusUI.js
* P5.js

Transmitting values to pd4web from p5.js cannot be done from draw() loop, but can be done from inside following functions, using sendToPureData()  :
* mousePressed()
* mouseDragged()
* mouseMoved()
