# NTS-1-Control-Panel

Control panel to edit/save/load presets for the Korg NTS-1 synthesizer. It also lets you send MIDI note and CC data from a MIDI controller to the NTS-1.

Included is a configuration file for using an Akai MIDI Mix as a controller to send CC messages to the NTS-1. If you're using a different MIDI controller, you can create and save a configuration file for it (feel free to submit it for inclusion in future releases).

You can also create and save presets for patches to run on the NTS-1. 

Dependencies:

1. Pd v0.51.3 or later
2. iemlib v1.22 or later

Changes (v1.0):

1. Fixed some bugs
2. Added limited support for arpeggiator
3. Added 30 presets (patches)
4. Added control to monitor audio levels
5. Added randomize function to generate presets
