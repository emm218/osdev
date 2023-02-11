# Emmy's OSdev Silliness

this is my third attempt to make an operating system for actual hardware

already its gotten farther than my last 2

an auspicious sign

## Roadmap

1. write a script to generate bootable images from the efi loader and kernel
   binary that cargo generates
2. have the loader get a memory map and pass control to the kernel ASAP
3. figure out memory layout (64 bit space is so ridiculously large!) and write
   paging
4. serial driver and link with gdb stub for debugging over serial
5. write a memory allocator (first fit implicit free list should work well
   enough, can work on performance later)
6. file system driver (FAT first probably, but then others)
7. ELF loading
8. syscalls
9. multitasking

...and I'll make the rest of the choices when I get there. 

In no particular order some other things I want:

- multi core support (my computer has 4 cores after all)
- ethernet (and maybe WiFi eventually?)
- graphics driver
- get to self hosting!
- more interesting ideas so this isnt just the 98274395273659137th Unix clone

