pyty-h
======
A Simple Typewriter Sound Emulator for Linux
--------------------------------------------

pyty-h is a rip-off. I am not a programmer, so all credit is due to Michael Holler (https://github.com/mikeholler). His pyty (https://github.com/mikeholler/pyty) is an awesomely simple program that transforms your linux station onto a noisy typewriter of old.

pyty-h is just pyty with a few minor changes. I have no knowledge of python, but Michael Holler's code was simple enough to allow me to play around a bit with it.

The only major change worth noting, and that might be useful for anyone trying out this version (please don't!!1) was to add the flag '-f <any number> to mpg123, allowing some control on the program's volume, so to make it less painfully intrusive with other competing sounds on the system (music player, for instance, especially if you are using headphones). Please note that the default volume for mpg123 is 32768. As stated in mpg123 --longhelp:

```-f <n>, --scale <n>        scale output samples (soft gain - based on 32768), default=32768)```.

The rest of the changes are just customizations of sounds. I did it just because ¯\(º_o)/¯. The code is so simple that I allowed myself to goof around a bit. Nothing to see here, unless you want to undone everytihng I did (mostly recommended).

The rest is with Michael and his readme file. His instructions make this work.



Installation
------------

**pyty was written on/for Ubuntu Linux, but it should work for any Unix-based
operating system**, provided it is running X and has the correct dependencies
installed.

What are the dependencies, you might ask? Here they are:
- **python3-xlib** -- a Python library to interface with X
- **mpg123**      -- a command-line based mp3 player

On Ubuntu, these dependencies can be installed by running the following
command:

    sudo apt-get install python3-xlib mpg123

### Starting pyty ###

Starting pyty couldn't be easier. Just open up a command prompt and type:

    python3 /path/to/pyty.py &

Or simply:

    /path/to/pyty.py &

You're good to go!

Closing Remarks
---------------

I certainly didn't write this without inspiration, and if my program inspires
you, all the better! **Feel free to fork, modify, and/or pull request.** Or, of
you're not that outgoing, at least open an issue if you'd like a feature added
or find something wrong with the program. I love collaborating with people, so
bring it on!

Enjoy!
