# Mathematical-Illustrations
A place for code and files associated with the Mathematical Illustrations meetup, put on by the Minions of Math

On the 25th of July, 2017 the Philadelphia Minions of Math did a Google Hangout based on the book Mathematical Illustrations
by Bill Cassleman. The book covers geometry done in Postscript and it was mentiond at the meetup that it would be a good idea
to keep track of problems and scripts on Git Hub. It is the goal of this repository to keep track of the nessacary files needed
for making the meetup a smoothly running operation. At the moment, this is kept up by Samuel Bledsoe but hopefully more people
can add files as needed.

Installing Ghostscript:

Mac/OS X: Ghostscript is no longer bundled; i.e. no "gs" command.

An older unsupported version of GhostScript is available on SourceForge and homebrew is another possibility .

At the moment, the latest version of GhostScript is at https://www.ghostscript.com/ . Version 9.2.1 doesn't support OS X, but
an older ghostscript-8.71-mac is at http://downloads.ghostscript.com/public/old-gs-releases/

Installed it in /Users/Shared/ghostscript with no problems, except it uses the X11 window system, which Apple no longer bundles...

For more documentation: "About X11 for Mac" at https://support.apple.com/en-us/HT201341 . Installation of XQuartz may not be
a problem. Compiling X11 from source is an option, but this may not be the best solution for the beginner...

CAUTION: DO NOT just grab a copy of GhostScript off the net from such outfits as Softonic, Winsite, etc. They will bundle 
stuff you do NOT want...

(This is an edited comment from Minion of Math George Zipperlen)

Linux: At the moment, Ghostscript comes with most distros. Open your terminal window and type

>gs

and see if you have it. If not, for Ubuntu:

>sudo apt-get install ghostscript

As time goes on, this will be updated with more information on installing and running ghostscript/postscript
