# SWTPC 6800 MP-8M Memory Board

## Description

The MP-8M Memory Board is a 5 1/2 x 9 inch board with a total storage capability of 8,192 (8K) words of a 8 bit random access memory.
The circuitry on the board provides all of the address decoding and data line buffering to handle a total of 16 4K (4K bit x 1 bit) static RAM ICs.
All interconnections to the system are made via a 50 pin connector to the Mother Board (MP-B); the so-called SS-50 bus.
Current consumption for the entire board (8K of memory plus decoder/buffer) is approximately 1.5 A.

> Introduced by Southwest Technical Products Corporation in 1977.
> The MP-8M kit did cost $250.

## KiCAD Libraries

### Pull the custom library repository

This circuit uses symbols and footprints from a custom library, to be added as a git submodule.
On creation of this repository, this library must be added as a submodule by running the command `git submodule add https://github.com/crazyelectron-io/KiCAD_custom_parts.git library/custom_parts` once at the root of the repository.
Whenever the custom library is updated in Github, it can be synced with this repository by running `git submodule update`.
And the commands `git submodule init && git submodule update` imust be run once after the repository is cloned.

### Add custom libraries to KiCAD

To use the libraries in the project, they must be added once as symbol or footprint library.
The following symbol libraries are used:
 #TODO:

And the footprint libraries:
 #TODO:
