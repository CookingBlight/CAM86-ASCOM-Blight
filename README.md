# cam86 ASCOM driver
Custom ASCOM driver for CAM86 DIY camera (Sony ICX453AQ sensor). Only confirmed to be compatible with custom low level driver written in C++.

Because the ASCOM driver doesn't work with the other firmware and low level driver found elsewhere I have created a new repo instead of a fork.

This project is based on work of Ukrainian telescope amateurs.
Most of their work is shared on this huge [forum thread](http://www.astroclub.kiev.ua/forum/index.php?topic=28929.0).

The current work is described [here](http://www.iceinspace.com.au/forum/showthread.php?t=146493).

The source code for the camera firmware can be found [here](https://github.com/CookingBlight/CAM86-FW-Blight) while the low level DLL can be found [here](https://github.com/CookingBlight/CAM86-DLL-Blight).


# See also
[Information in Ukrainian](http://astroccd.org/)

[French forum](http://www.webastro.net/forum/showthread.php?t=141764)

[Cam84/Cam86 forum](http://www.cloudynights.com/topic/497530-diy-astro-ccd-16-bit-color-6mpx-camera/)


# Authors:
Gilmanov Rim (Гильманов Рим) - original camera hardware and low-level camera interaction

Sergiy Vakulenko - Original ASCOM driver 

Their code is shared on [Sergiy Vakulenko 's Github](https://github.com/vakulenko/CAM8_software)


Luka Pravica - current modifications/extensions/customisations to the firmware, low-level driver and ASCOM driver

Tommy Ramberg - Modified driver to be compatible with low level driver written in C++.

All derived work from this code must be kept free and opensource as governed by GPL v2 or later (see the included file COPYING).
