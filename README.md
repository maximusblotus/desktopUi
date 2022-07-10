# DesktopUI.js

Created by Max Blotas on the behalf of The Maxtrix in 2022

DesktopUi.js is a simple javascript library to create mutliple draggbale and resizable window like divs, just like on desktop environement. Have fun dragging!

⚠️ DesktopUi.js hasnt been created nor tested for touch based interface.

### How to set up:

To intiate desktoUi you first need to create an object named desktopUi in your main.js
desktopUi{} need to be defined before desktopUi.js is called as it should define your variables.

For the library to function properly the object desktopUi{} need to contain a set of propreties (see framework below):

            let desktopUi = {
    [mandatory]     container: div,                  //
    [mandatory]     els: div,                        // defines the window elements
    [mandatory]     handles:  div,                   // target the handle
                    resizer: div,                    // target the handle
                    minSize: int, (in pixels)        //
                    maxSize: int (in pixels)         //
     };

### This script is 100% open source → use it & tweak it as you wish
