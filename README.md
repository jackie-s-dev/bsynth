# BSYNTH 

## Basic specifications 
The BSYNTH shall be a command-line application to run a synthesizer that is compatable with the Casiotone CT-S200 and it's USB-MIDI.

## Desired commands 
	- BSYNTH [-p port] [-t tone] [-v volume] [-r record] [-k keyboard]
	- p {port} => specify the USB port for MIDI 
	- t {tone} => specify the desired tone, numerically 0-100 
	- v {volume} => adjust the volume 
	- r {record} => record the MIDI to the specified output file along with the specifications as headers 

## Project 
	[] Succesfully read MIDI from the USB connection 
		[] First make it just ASCII keyboard capable 
	[] Succesfully create live sound output 
	[] Create BASH capability to run basic synth from command line 
	[] Implement helper functions to modify the synth input/output
	[] Distribute?  
# bsynth
