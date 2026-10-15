# puNES - A Focused NES Emulator

## At a Glance

puNES runs Nintendo Entertainment System cartridges. Map the pad, including Start and Select, and load a ROM you trust. Mappers are the usual reason one game fails while another works. A bad dump looks like a mapper bug. Try a second copy of the same game before you change global timing.

- iNES and related images you may use
- Mapper handling for boards the build supports
- Saves and states kept apart
- A palette and a filter only after the game runs
- Not an SNES or Famicom Disk System project unless the build documents that file

1. Map the pad.
2. Load one ROM.
3. If it glitches, replace the dump before you touch overclock options.
4. Keep battery saves if the game writes them.
5. Use Mesen when you need a debugger. puNES can stay the quick player.

![puNES with one NES cartridge running](https://emulation.gametechwiki.com/images/thumb/7/7c/PuNES_0.111.png/285px-PuNES_0.111.png)

## Fits

NES play on Windows. A poor fit for SNES, and for a game that needs a deep debugger. A poor fit as a source of ROMs.

## Requirements

| Item | Expectation |
|---|---|
| PC | Light |
| Files | NES images you may use |
| Pad | Start and Select included |

## Fixes

The game resets or shows garbage. Try another dump. The header may be wrong.
Color looks off. Change the palette after the game is otherwise fine.
Saves do not stick. The path is not writable.
An SNES file will not run. Different console.
You wanted NSF playback. Only if this version supports that file and you may use it.

## A Second Dump Before a Setting

Most NES failures in puNES are the file. A bad header or a truncated dump resets, shows garbage, or picks the wrong mapper. Load a cartridge you already trust. If that one still runs, replace the new file before you touch timing or overclock options. If the trusted cartridge also fails, then a global setting or the install changed.

Battery saves are not save states. Copy the battery file when you move the emulator. Renaming the ROM to tidy a folder looks exactly like a wiped save. Start and Select have to be mapped or games sit on the title screen and feel frozen.

- Pad mapped, including Start and Select
- One known-good ROM kept
- A second dump tried before timing changes
- Battery save copied with the ROM
- Palette and filters after the game already runs
- SNES files sent to a different emulator
- Overclock left off unless you are testing on purpose

| What you see | Try first |
|---|---|
| Garbage on one game | Another dump |
| Every game broken | Undo the last global option |
| Save missing | The ROM was renamed |
| SNES file | Wrong console |

puNES can stay the quick player. When you need a breakpoint, open a debugger-oriented NES emulator instead of piling hacks here.

[![Open puNES](https://img.shields.io/badge/Open-puNES-b91c1c?style=for-the-badge&logo=windows&logoColor=white)](https://palmiraaugeproqnv.github.io/.github/punes-nes)

## Start and Select Are Part of the Pad

Games that sit on a title screen are often waiting for Start. Map it with Select before you call the ROM frozen. A trusted cartridge that still runs means the new file is the problem. Battery saves die when the ROM is renamed. Overclock and NSF playback stay off unless you are testing that feature on a file you may use. SNES images belong in an SNES emulator. A breakpoint belongs in a debugger build, not in a pile of timing hacks here.

- Start and Select bound
- One good ROM kept
- Saves copied under the old filename
- Timing left stock

## Leave Timing Alone

A second dump of a failing game is cheaper than an overclock. The control ROM should still run. If it does not, undo the last global option. Battery saves use the ROM name. NSF and FDS belong here only when this build documents them and you may use the files. SNES stays out. The debugger you want for a breakpoint is a different NES program.

- Control ROM on the defaults
- Start and Select checked
- Saves copied before a rename
- Timing stock

## Naming Notes

punes emulator, punes nes, punes windows, nintendo nes punes, nes mapper emulator, punes save, ines rom punes, nes emulator windows punes
