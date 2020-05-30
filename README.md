# Hex-Code-Picker
Get the hex code of a pixel in TouchDesigner

Quickly-made TOX that takes the information from a pixel of the panel and provides the HEX code in a Text TOP. You can also type in a HEX code in a Field COMP and get the resulting color. Might come in handy somewhere.

#### NOTES
* This is set for a 1280 x 720 resolution. For other resolutons, be sure to update Math1 and Math2 CHOPs.

#### TO DO
- [ ] Create an interface
- [ ] Add error catching


#### drmbt edit
Cool tool hopeliz! I've needed something like this a few times and always half assed what I ended up with, so I'm grateful that you shared something like this. I hacked it a bit to fit the way i would work with it at the panel level in a project, and added a few feauters 

-adapted custom tox to pass the signal through and output to TOP CHOP and DAT space
-movie file in is now feeding an In TOP, which provides resolution
-Math method updated to range
-Labeled tops that feed a data reference
-Field can now be driven from custom parameters
-panel gets adjustable border for visual feedback of sampled color
-hold method eliminated, sampling is from panel uv while selected

#### TO DO
-maybe add some analysis top information about averages in the input
-add luminousity conversion