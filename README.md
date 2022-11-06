# DIY audio source controller
## Problem

I have a pair of good audio monitors and want to reuse them between different audio sources.
Extra points if I don't need to move from the couch.

## Solution

Use esp32 and make a network enabled audio source controller.

## Details

* Uses low signal latching relays
* Relays can be driven directly from esp32 using 3.3V gpio ports
* Supports 3 stereo audio inputs and 1 stereo audio output
