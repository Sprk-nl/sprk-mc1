# sprk-mc1
SPRK Music Controller 1

This project has changed from design to hardware ordering phase.
Next-up will be the breadboard and code part.

What will this Midi / Music controller do?

## Functions
### left rotary
- Press once to show menu on top half turn to select, press again to choose.

### Right rotary
- Change the last selected function on screen


**To get there, I have a few primary objectives:**
- Powered via USB
- Advertise as MIDI HID device via USB
- Draw 4x4 pad on screen
- When a pad is selected, mark it, by re-color the fill or border
- Leave room on the top for additional information
- Send out MIDI note or CC

** And sure, seconday objectives will make all the fun, so share you requests with the project.
- Sync to MIDI clock as slave
- print synced BPM on screen, with a 4 count
- Able to quick add an LFO to a pad, static of learn dynamic on the fly
- Read SD card data, for menu config
- Add a distance controller with IR/sonar
- draw LFO on screen and send out
