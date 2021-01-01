# ccleste

[Original repository](https://github.com/lemon-sherbet/ccleste)

This is a quick switch port of the SDL port by [lemon-sherbet](https://github.com/lemon-sherbet) of the classic celeste made in PICO8 by Matt Thorson & Noel Berry



# Switch port

To compile for the switch, you will need devkitPro with the following packages:

switch-sdl2
switch-sdl2_mixer

Use the command:
make -f Makefile.switch

The cceleste folder (generated in the release folder if you built it yourself) should contain the data folder and be put at the root of the sdcard. I couldn't test with an actual switch yet.

If you're using Ryujinx emulator, go in the ryujinx folder (File-> Open Ryujinx folder) and put the cceleste folder inside of the sdcard folder.
You should have  sdcard/cceleste/data. 

If you're stuck at the Loading screen, it could because the data folder could not be found.




## Original credits by lemon-sherbet (I replaced "I" by "lemon-sherbet")

Sound wave files are taken from [https://github.com/JeffRuLz/Celeste-Classic-GBA/tree/master/maxmod_data](https://github.com/JeffRuLz/Celeste-Classic-GBA/tree/master/maxmod_data),
music ogg files were obtained by converting the .wav dumps from pico 8, which lemon-sherbet did using audacity & ffmpeg.

All credit for the original game goes to the original developers (Matt Thorson & Noel Berry).

## credits

I started working from [MVG (Lantus)](https://github.com/lantus) 's makefiles for the switch ports of [chocolate doom](https://github.com/lantus/chocolate-doom-nx) and [Cannonball (the OutRun engine)](https://github.com/lantus/cannonball-nx).


