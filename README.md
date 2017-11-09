# lnk-generator

# Batch Windows Shorcut Creator

[![Download lnk-generator](https://a.fsdn.com/con/app/sf-download-button)](https://sourceforge.net/projects/lnk-generator/files/latest/download)

batch create windows shorcuts, great tool for emulator front-ends that have problems running directly.

author: jasenmichael

lnk-generator.exe

this is a windows program written in Auto Hot Key - autohotkey.com

this program needs all 6 parameters

USAGE:

lnk-generator.exe ["1"] ["2"] ["3"] ["4"] ["5"] [6]

1: full path to the launching .exe

2: full path to working directory 

3: arguments to add

4: directory of files to be launched with %1%

5: full path to shortcut directory

6: file extention without . or quotes

EXAMPLE:

"c:\lnk-generator.exe" "C:\Dolphin\dolphin.exe" "C:\Dolphin\" "/b /e" "C:\emu\roms\wii" "C:\emu\roms\wii\shortcuts" iso
