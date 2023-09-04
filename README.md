
# Pico Held hardware files

Here you can find the PCB design files, BOM and CPL files, STL files of the case, schematics, components and datasheets for the *Pico Held* - a handheld based on the *Raspberry Pi Pico*.

The hardware project is released under the *Creative Commons NonCommercial license* (BY-NC, non-commercial use).

I am currently still looking for a distributor, so currently the only way to get a *Pico Held* is making your own PCB and case.

## Disclaimer

Please note (as also stated in the liscense): This design and all the files provided come without any warranty. I cannot be held responsible for any damage that might be caused. You build/operate at your own risk.

## Instruction video

This [Youtube](https://youtu.be/bDk0hH1kbgg) video demonstrates how to assemble the *Pico Held*.

## Case

I had the cases printed over at *JLCPCB* (no affiliation) using resin printing with - in my eyes - a very good result.

## PCB production parameters

Some notes for PCB production:

PCB thickness needs to be 1.2 mm (this is important for proper button haptics). Vias need to be untented for the recovery mechanism on the back to work. (Short the exposed via on the back side to ground when turning on the *Pico Held* to force bootloader mode).
Also, choosing "HASL leadfree" is definitely advised.

![PCB assembled](board/board_assembled_photo.jpg)

## Parts sources

Here is where I sourced some of the parts (no affiliation):

µSD card slot:
aliexpress.com/item/32892777587.html

audio board:
aliexpress.com/item/1005002097528890.html

LCD (choose "3.2 NO TOUCH 40P"):
aliexpress.com/item/1005004769761714.html

speaker:
aliexpress.com/item/4001277480820.html

analog stick:
Any for the PSP1000 will do fine.

RPi Pico:
Both a "regular RPi Pico" as well as a "Waveshare RP2040-Plus" will fit.

## Support

If you like my work and would like to support me you might want to consider buying me a coffee :)

<a href="https://paypal.me/kammerdaniel/"><img src="blue.svg" height="40"></a>  

(Image by github.com/andreostrovsky -- Thanks!)
