Kinesis Advantage 2 macros that Charles uses.
==========

I've used a Kinesis Advantage for 20 years now, and there's a few simple remappings
and macros that are helpful to me. Now that Advantage 2 exports mappings in text readable
format, I can back them up and share them easily.

How to use
======

To install these on your keyboard, see the Power User Model in the user manual
https://www.kinesis-ergo.com/support/technical-support/manuals-drivers/.
In particular, read the sections about the V-drive. I copied these files off my V-drive.


Mappings
======

thumb_mappings.txt
------

This is the mappings file you want to use on your keyboard. 
You can paste its contents into `1_qwerty.txt` etc.

Basically, this moves parents and brackets onto my thumb keys
and escape into the main keyboard. I found that I was using
these a lot when I program. 
This file does the following things:

 * Moves the escape key into the main keyboard, and = down to caps lock.
 * Moves hyphen onto a large thumb key (Del)
 * Put `(` and `)` under my left thumb (these I don't use as much)
 * Put `{` and `}` under my right thumb
 * Put `[` and `]` under my right thumb with either shift key

thumb_mappings_commented.txt
------

This is the same as `thumb_mappings.txt`, but with comment lines
that say which of the remappings does what. DO NOT copy this 
onto the keyboard. It's just for you to read if you want to
understand the file contents more.

1_dvorak.txt
------

This is a backup of the exact mappings that I use on my keyboard.
It's different than `thumb_mappings.txt` in that:
* `1_dvorak` contains
some remappings for Mac mode, like putting the command key on your
thumbs, which I think the keyboard added automatically? But it's been
long enough that I don't remember 100\% about that.
* For `thumb_mappings`, I rearranged the order of the lines to group
related remappings together, in case you want to read them.

Other resources
======

Another great set of mappings is https://github.com/jcowgar/kinesis-advantage-2.
