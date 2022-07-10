# DesktopUI.js

# ⧉⧉⧉⧉⧉⧉⧉ DESKTOP-UI.js ⧉⧉⧉⧉⧉⧉⧉⧉

Created by Max Blotas on the behalf of The Maxtrix in 2022

### How to set up:

To intiate desktoUi you need to create an object named desktopUi in your main.js
It need to be defined before desktopUi.js is called

For the library to function desktopUi{} need to contain a set of propreties (see framework below):

    let desktopUi = {
    [mandatory]   container: div,               //
    [mandatory]   els: div,                     // defines the window elements
    [mandatory]   handles:  div,                // target the handle
               resizer: div,                    // target the handle
               minSize: int, (in pixels)        //
               maxSize: int (in pixels)         //
     };

# This script is 100% open source → use it & tweak it as you wish
