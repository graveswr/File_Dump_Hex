# File_Dump_Hex
Hex File Dumper for Windows - Written In C++ Under Embarcadero CLANG for 64 and Embarcadero Borland for 32 Bits Using the Microsoft VCL.

I wrote this program in about two hours because I couldn't find a hex dumper which I liked.  Feel free to share it under the GPL. It runs under Windows 7 or later.  The release versions are for 32-bit and for 64-bit Windows.  All of the object codes are linked, so there's no formal install.  All you have to do is to copy the executable file and run it.  The Rapid Development Environment used is the Embarcadero Seattle module.  You'll have trouble compiling this without an Embarcadero C++ compiler.  I believe that they have a trial offer for a one month evaluation if anybody is interested.  They're a little pricey but excellent compilers.

Bill


Operating Instructions:

At the moment, this jewel only has one command.  It's 'Read Binary File' in the FILE menu.  It will take you into a standard Microsoft file selection dialog.  This operates in the standard way. When the selection is made, a new window will open with the file dumped in Hex and ASCII.  In the ASCII portion, the non-rendering chars are stated as a null.  You can open as many windows as you like simultaneously to compare files.  Opens and closes are logged to the system log on the splash window. 

If anyone actually uses this, I'll occasionally post improvements.

COPYRIGHT (2016), William R. Graves, All Rights Reserved.  Licensed under GPL 3.0.

