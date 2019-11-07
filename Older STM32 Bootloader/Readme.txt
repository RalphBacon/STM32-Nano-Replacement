PLEASE READ BEFORE FLASHING!!!

This is an older bootloader for STM32 clones that simply don't work
with the current bootloader (USB device not recognised, under Windows).

This version worked with all my devices that had the above issue and
pointed to not having genuine STM32 chips... allegedly.

After flashing with THIS version of the older bootloader it worked
as you would expect.

Initially you might get a new device type in our DEVICES list (Windows 10)
but as soon as you load your first sketch you get the Maple (COM XX) under 
Ports as you expect.

Thanks to Glenn Rice who pointed me to the source of the new bootloader
which you can download yourself if you prefer:
https://github.com/rogerclarkmelbourne/STM32duino-bootloader/blob/d19bcaf1ef044eb5e09b772f7a1d7c158c3c2976/binaries/generic_boot20_pc13.bin

The copy here is as it was in that github in November 2019. Just in case
that link disappears!

This bootloader also worked for me with GD32 chips and CKS32 chips too, very
common substitutes on eBay and from Asain warehouses.

Ralph Bacon November 2019
https://www.youtube.com/ralphbacon video #152