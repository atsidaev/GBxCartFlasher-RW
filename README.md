# GBxCartFlasher-RW

This is a crossover between two Game Boy cartridge dumpers - `gbcartflasher` (project from 2007 by Kraku & Chroost) and `GBxCart-RW` by insideGadgets.

Actually, this is a port of `GBxCart-RW` firmware to `gbcartflasher` PCB. This was required to make dumper work with convenient `FlashGBX` client program by Lesserkuma.

Warning: while `GBxCart-RW` has GBA support, `gbcartflasher` hardware doesn't. So be careful and don't try GBA cartridges with this device.

## How to use

TODO: write instructions

## Why I did this

Because I ordered a bunch of `gbcartflasher` PCBs before I realized that `GBxCart-RW` is more improved while using almost the same hardware. 

## References

1. gbcartflasher firmware: https://github.com/Tauwasser/GBCartFlasher (there are two verions, original fw is inside 'hardware' branch)

1. gbcartflasher PCB: https://github.com/melka/gbcartflasher

1. GBxCart-RW repo with schematics and old firmware: https://github.com/insidegadgets/GBxCart-RW/

1. FlashGBX client software for GBxCart-RW: https://github.com/lesserkuma/FlashGBX/