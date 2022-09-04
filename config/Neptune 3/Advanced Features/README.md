As of 8-15-22 it seems there may be new screen firmware files, get them from here: https://github.com/mlee12382/Neptune_3/tree/main/Screen%20firmware/V1 or from the Stock D folder.<br><br>
"WIFI" firmware PROBABLY doesn't actually enable wifi, and if it does there may not be a way to access network settings, it compiled without error though so figured I would throw it up as an experiment. If it does actually work PLEASE let me know :D if not hopefully there are other ways to make it work. <br><br>
There are separate configs both with and without nozzle preheating for Auto Leveling.<br><br>
Test them out and see which version gives the most consistent results, stock firmware preheats the bed only.<br><br>
The Filament run-out sensor only works when the current Z height for the print is above 0.8mm, this is controlled somewhere in the stock firmware code and I don't have the coding skills yet to find this and change it.<br><br>
This is built on Marlin 2.0.93 as that is what elegoo built theirs on and they've unfortunately made changes to the core source files that make it so I wasn't able to port to 2.1.1 as of yet, my source code modifications are available here: https://github.com/mlee12382/Neptune_3<br><br>
Instructions for flashing the firmware and the screen firmware files are in the stock folder one level back.<br><br><br>
9-4-22 - Rolled in v1.0.4 updates, which enabled probe tare. Should display 1.0.4.A for Advanced Features.<br><br>
8-24-22 - Minor tweak to firmware to attempt to get M600 to resume after changing filament.<br><br>
8-18-22 - Rolled in Stock Firmware 'D' changes.<br><br>
8-7-22 - Minor tweak to Z-offset.<br><br>
8-6-22 - Updated Z height after Auto Level.<br><br>
8-6-22 - Rolled in bugfixes from Elegoo.<br><br>
8-5-22 - Disabled run-out sensor until mmore informations can is received from Elegoo on proper configuration.<br><br>
8-5-22 - Inverted Run-out sensor logic.<br><br>
8-4-22 - Increased run-out sensor distance.<br><br>
8-4-22 - Experimental wifi firmware added.<br><br>
8-4-22 - Added Filament Runout sensor compatibility, made separate ABL configs for nozzle preheat. <br><br>
8-3-22 - Updated PID values for heated bed, enabled preheat for ABL, reduced ABL grid to 4x4 to match screen.<br><br>
8-1-22 - Uploaded version 1 of Neptune 3 firmware for testing.
