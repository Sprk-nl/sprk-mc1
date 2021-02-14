# SPRK-MC1
SPRK Music Controller 1

![alt text](https://github.com/Sprk-nl/sprk-mc1/blob/main/image/SPRK-MC1_Small.JPG?raw=true)

This project has some stages, of which the bold one is active
- Sketch design
- **Hardware order** (see BOM)
- Breadboard
- Code primary objectives
- Code seconday objectives
- 3D design case
- print case
- Expand Feature

# What will this Midi / Music controller do?

## Functions
### Touch screen
- select one (or multiple) pads from the 4x4 on screen to select a midi CC value to adjust
### left rotary
- Press once to show menu on top half turn to select, press again to choose.
### Right rotary
- Change the value of the selected pad(s) on screen.


**To get there, I have a few primary objectives:**
- Powered via USB
- Advertise as MIDI HID device via USB
- Draw 4x4 pad on screen
- When a pad is selected, mark it, by re-color the fill or border
- Leave room on the top for additional information
- Send out MIDI note or CC

**The seconday objectives will give it all the fun, so share you requests with the project.**
- Sync to MIDI clock as slave
- print synced BPM on screen, with a 4 count
- Able to quick add an LFO to a pad, static of learn dynamic on the fly
- Enabling deep-page to attach menu's to hardware / midi channels, and switch easily in-between.
- Read SD card data, for config
- Add a distance controller with IR/sonar
- draw LFO on screen and send out
- Save custom LFO's
- select X-Y functions and draw the X-Y position, with the option of adding an LFO
- Have a complete other purpose with the same design?
  - IRC chat integration to notify and show you (tagged) messages
  - Work with processing to adjust other pheriples or video equipment
  - act as an OBS short-cut keypad
