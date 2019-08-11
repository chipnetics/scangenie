# ScanGenie VGA Scanline Generator


**View this project writeup at https://chipnetics.com/projects/hw/scanlinegen/**

_SCHEMATIC (.dch) and PCB (.dip) require Diptrace_

_This work is released under: Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)_

The ScanGenie is a RGB scanline generator is a nice and simple little project for anyone looking to relive the CRT days. Personally I believe this simple design is the best scan line generator for your classic videogame consoles for generating lcd scanlines!  It is lagless, runs perfect with no external power, and gives crisp results on 240p and 480p signals.

The power runs off 5V from Pin-9 of VGA. If your source does not provide 5V on Pin-9, which commonly is the case, you can also power it using sync with no problems as the setup time of the logic chips is extremely minimal.

The board design is very simple utilizing just two chips by Texas Instruments, the SN74LS74 & SN74LS125.
