# Ableton_Lightframe

## Overview

This program provides a visual midi-editing mainly for Launchpad.

## Function Implementation

### Basic usage

The buttons in the left-bottom are launchpad buttons, it will turn green if pressed, light green if it is pressed last frame. Let's say every time you operate and get a "**track**" with the buttons, and get a "clip", which is the final midi file.

**New** - Create a new frame

**Reset** - Reset now frame

**Copy** - copy everything about this track

Save - save this track to specific directory

### Quick operation

**CW** - rotate now frame CW

CCW - rotate now frame CCW

180 - rotate now frame 180 degrees

Reverse - The last frame becomes the first frame, etc.

FlipY - Flip the Y position

FlipX - Flip the X position

### Combination method

**Flow** - Simply combine the track and the colors, if there are many colors, then it will show the next color in the next frame, you can use it to easily make something like "flowing rainbow".

**Bunch** - If you have many different sets of track and colors,put them in a big list and bunch them respectively.

**Snake** - Keep the last button lighted.

**Show** - If you click a saved clip, press "Show" to show it in the right.

**Frame** - Create a frame page and design it freely.(TODO)

### Options

**Name** - The name of track/colors/clip

**Interval** - How long a frame is, with the unit of beat.

**Wait** - The last button will wait the correspond time.

**Inherit** - The new frame will inherit the last status or not, just for easier edit.

**Add** - If checked, it won't save the clip immediately, but will concatenate the clip with the next clip until this uncheck.

### Colors

**Add** - Add the chosen color to now palette.

**Reset** - Reset now palette.

**Save** - Save now palette to specefic directory.

## PS

I didn't know how to use eyedrop before I write this, after I'm skilled at eyedrop I think this will be only used in very limited few situations.
