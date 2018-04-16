# MECCA-platform
The Music Education, Composition, Creation Application.

You are the student.
You are the composer.
You are the creator.

Aiming to unify the process of learning, writing and performing music. Because once these are realized as all part of a single activity, life will finally be [a dream](https://www.youtube.com/watch?v=0TgrorCZg80). We must subtly encourage "desirable" musical idioms while preserving maximum expressive potential, like the ultimate teacher who inspires and empowers you, the student, the composer, the creator.

Written completely in bash shell using simple scripts to generate waveforms and automagically stitch them together. 

## Dependencies
MECCA uses [sox](http://sox.sourceforge.net/), the Swiss-Army Knife of audio manipulation. Your distro might already have it.
If not:

    $ sudo apt-get install sox

## Windows:

Install [MinGW](http://www.mingw.org/) and add it to your system PATH according to [these instructions](http://www.computerhope.com/issues/ch000549.htm) 

## Usage

    $ chmod +x bass.sh
    $ ./bass.sh

This will produce triangle wave samples for the notes C2 - B3, in half, quarter, and eighth-note lengths as well as a double-eighth note sample for each. 

Then, start the synth:

    $ chmod +x synth.sh
    $ ./synth.sh
    
You can now jam on your keyboard in 2 full octaves:

     2 3   6 7 8
    q w e r t y u i
     s d   g h j   l ;
    z x c v b n m , . /


## TODO:

Provide scripts for common chord progressions for use as sequencing templates.

## LICENSE

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.
