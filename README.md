# draaaaaagble.js

Created by Max Blotas on the behalf of The Maxtrix in 2022

draaaaaagble.js is a lightweight, fun & easy to use javascript library to create mutliple draggbale and resizable window, just like on desktop environement. Have fun dragging!

⚠️ DesktopUi.js hasnt been created nor tested for touch based interface. sorry phone addict...

### How to set up:

To intiate draaaaaagble you first need to create an object named draaaaaagble in your main.js
draaaaaagble{} need to be defined before draaaaaagble.js is called as it should define your variables.

For the library to function properly the object draaaaaagble{} need to contain a set of propreties (see framework below):

            let draaaaaagble = {
    [mandatory]     container: div,                  //
    [mandatory]     els: div,                        // defines the window elements
    [mandatory]     handles:  div,                   // target the handle
                    resizer: div,                    // target the handle
                    minSize: int, (in pixels)        //
                    maxSize: int (in pixels)         //
     };

#### This script is 100% open source → use it & tweak it as you wish
