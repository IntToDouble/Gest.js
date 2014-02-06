gestRec.js
=======

Javascript Gyroscopic Gesture Recognition Library

## Usage

At the time of writing, using `gestRec.js` is a simple two part process after including the library in the source of the page using something similar to the following:

`<script type="text/javascript" src="gestRec.js"></script>`

After the library has been loaded, the next step is to assign the callback function for each gesture you would like to be recognized. The following gestures are currently recognized:

`["flip","flick","twist"]`

To assign a callback for any of these gestures, call `gestRec.set()`, similar to the example provided below:

`gestRec.set(gestureName, function() {...});`

Last but not least, to begin the gesture recognition, gestRec.init must be called to initialize the device event handler through which all motion is received:

`gestRec.init();`

## Demo

http://IntToDouble.github.io/gestRec.js/examples/alert/coloredDiv/


