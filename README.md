# Mackie-Universal-Chataigne-Module
A Chataigne module for the X-Touch Series and other Mackie protocol compatible MIDI Controllers

###Changelog 
1.1.0
Optimization of scanning through values
Bug Fix
- Strip 1 rotary Read only to match others
- UTC offset update

1.0.4
Bug Fix
- Make sure clock is updated consistantly (force draw every 1.5 seconds)
- Force faders to go all the way from 0 to 1, instead of .999

1.0.3
Bug Fixes
- Encoder Assign lights fix Enum parameter
- Main fader touch
- Bank Prev and Bank Next are now represented in Values.misc as well. The values were there, but not implemented, now they work.
- Strip Index, Active View, and Encoders Assign parameters are checked on startup, and sent to the device.
- Sequence time now checks to avoid warning

1.0.2
- Added support for X-Touch Extender Scribble Strips
- Added support for scribble strip colors
- Fixed clock timing, updated to have proper timezone adjustment
- Added parameters to set clock source to a sequence, including partial seconds
- Wheel moved to transport, and triggers added for CW and CCW motion.
- General code readability updates (remove nested if else, where else is implicit in strip update function)
- optimize init function, and don't call everytime the fader and encoder names are switched

1.0.1

- Correcting Hours now based on Fr hour
- Solo update when 'flash on solo' changed
- Controler update when device changed
- New Bank Select
- New Encoder Assign section
- New View buttons section
- Adding all buttons interaction

Version 1.0