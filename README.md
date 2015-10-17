# Smart-Drum-Kit
Code for an Electronic Drum Kit coded in the Arduino IDE and implemented with the use of four simple button switches (input pulled up)synced to LEDs. Makes use of the MIDI (Musical Instrument Digital Interface) Protocol to transmit serial messages from the Arduino to a music synthesis software, such as Ableton or FLStudio, with the use of intermediary software 'Hairless MIDI' and 'Loop MIDI.' The musical notes synthesized in the Arduino Code are mapped to separate channels, which are again mapped to various beats in the musical software (namely Cymbal, Snare, Hat, and Kick).

Hairless MIDI- creates a pathway for the MIDI messages to the the music software. Needs another intermediary port, in the form of LoopMIDI.

LoopMIDI- creates a port for communication from Hairless MIDI output to FLStudio Input.
