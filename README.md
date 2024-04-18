# Mackie-Universal-Chataigne-Module
A Chataigne module for Mackie protocole compatible MIDI Controllers
WIP

Changelog 
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