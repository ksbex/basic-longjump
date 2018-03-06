# LONG JUMP for the TRS-80/Tandy Model 100/102


## Introduction
The object of Long Jump is to see who can jump the farthest.  You must run as fast as possible as far as possible without crossing the line before jumping.  Faster speeds will give longer jumps.  This is a recreation of a game that I made in the 80s for my TRS-80 Pocket Computer PC-3.  The PC-3 only had a single line display so the Model 100 allowed me to add some modest additional graphics, even with only 10 lines of code.  The original PC-3 game was inspired by "Summer Games" for the Commodore 64.

This was specifically done in 10 lines/80 chars per line as an entry in the 2018 BASIC 10 Liners PUR-80 category.
[BASIC 10Liners 2018][http://gkanold.wixsite.com/homeputerium/basic-10liners-2018]

## Gameplay
Run by pressing the F and J keys as fast as possible.  The time begins as soon as you press "f" or "j" the first time.  Get as close as possible to the line before jumping by pressing the spacebar.  Be sure caps-lock is not on.  Only lower case letters will count toward your speed.

## Files
[Github Repository](https://github.com/ksbex/basic-longjump.git)

  JumpGameplay.png	Screenshot of Long Jump gameplay
  JumpListing.png	Screenshot of Long Jump BASIC program listing
  JUMP.BA		Tokenized BASIC program for loading to emulator/computer
  JUMP.DO		ASCII BASIC program listing
  README.md		This file

## Emulation
VirtualT, the Model 100 emulator can be downloaded from https://github.com/ksbex/basic-longjump.git.  The macOS and Windows binary files are the easiest to set up.  Compiling from source and/or using the linux binaries can be tricky due to variations in shared libraries on different distributions.  

The timing of this game is geared toward running on physical hardware so be sure to set the emulation speed to 2.54MHz.

From the VirtualT file menu select "Load file from HD" and select JUMP.BA.  Select JUMP.BA from the menu to play.



