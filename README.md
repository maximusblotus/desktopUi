# draaaaaagable.js

#### Created by Max Blotas on the behalf of The Maxtrix in 2022

draaaaaagable.js is a simple, lightweight & easy to use javascript library to create mutliple draggbale and resizable window, just like on traditionnal desktop environement. Have fun dragging!

⚠️ draaaaaagable.js hasn't been created nor tested for touch based interface. I'm working on this!

### How to set up:

To intiate draaaaaagable you simply need to create an object called draaaaaagbale in your main.js or your html file.
draaaaaagble{} need to be defined before draaaaaagble.js is called as it should define your variables.

For the library to function properly the object draaaaaagble{} need to contain a set of propreties (see framework below):

    let draaaaaagable = {
        els: document.querySelectorAll(".windows-elements"),
        handles: document.querySelectorAll(".handle"),
        container: document.querySelector("#container"),
        resizer: document.querySelectorAll(".resizer"),

};

### Options:

> els and container are mandatory elements.

            let draaaaaagble = {
    [mandatory]     container: div,                  //
    [mandatory]     els: div,                        // defines the window elements
    [mandatory]     handles:  div,                   // target the handle
                    resizer: div,                    // target the handle
                    minSize: int, (in pixels)        //
                    maxSize: int (in pixels)         //
     };

#### This script is 100% open source → use it & tweak it as you wish
