# Pine-CL-GD5434
CL-GD5434-based ISA VGA card.
Tested, works, but may still contain minor errors. Feature connector and 64k rom option are not tested yet.
Notes:
1) R1-R5 are configuration resistors, install R2 & R4 for fast DRAM, R2 & R4 for slow DRAM. Check CL-GD543x databook if you need more info.
2) U10 - optional, provides DD2B support (works with generic PCI BIOS).
3) FB1-F1-D2-C68 - DDC monitor power, remove if not using U10. D2 - BAT54 or equivalent, F1 - 200mA poly fuse.
4) U11 - optional, 93C46 used to store video modes supported by your monitor.
5) U12, U13 - optional, ESD & hot-plug protection.
6) C90-C92 - 10uF - 47uF 6.3V+
7) D1 can be replaced with 1n4148
Creative Commons Attribution-ShareAlike 4.0 International License. See https://creativecommons.org/licenses/by-sa/4.0/.
