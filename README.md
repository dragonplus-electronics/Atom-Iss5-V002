Atom Iss5 Repro V002 (Replica using more modern components)
This board is intended to be used as a replacement Issue 5 board for the Acorn Atom. If you build it, please share your experiences via Stardot or other Acorn Atom online forums.

KiCad File Content
Wherever possible, custom symbols have been created in order to align closely to the structure of the original Atom schematics. The schematic itself though has been split into logical areas with off-sheet address and data busses as well as global pin assignments. When you open the project, you will likely need to 'Rescue' the symbols, as you will not have the custom libraries.

The PCB files themselves are not included in this repository, purely because at this stage I do not want people running off and creating all sorts of forks and modified boards. Please do not ask me for them, as refusal often offends. :) Those files will follow once all Atom repro work is concluded.

Although the PCB layout is close to identical in most respects, I have replace the archaic silkscreen symbols with more modern variants, as well as also using more standard pitches for component legs.

Main Changes for this Version
- Old ROMs replaced with 2764-27512 compatible pinouts. Pin-ties shown on board.
- Reset circuitry replaced by reset circuitry from another Acorn machine.
- Nearly every IC now has it's own decoupling capacitor.
- Crystal footprints are compliant to HC49 components, and allow crystals to sit flat.
- All board footprints/silkscreens updated to modern equivalents (all electrolytic capacitors are now radial; all ceramics are 2.54mm pitch.
- Old power regulators removed. Whole board is now on a single +5V supply.
- All 81LS95 and DM8304 chips replaced with LS245 (and hopefully will support HCT245)
- Parallel port LS245 has a header pin on direction in case it can be used in future designs.
- Board contains links and headers which will allow usage with the ROMRAM board without any mainboard modifications.
- Various areas of the board tidied up, including the discrete video circuitry and the tape audio op-amp circuitry. The tape op-amp is the only IC which has been re-located.
- Composite RCA socket footprint added where the old RF output would have been.
- Footprint added for 6-pin DIN RGB output for use by Colour/RGB board (only really for modern 3D printed cases with cutouts).
- Keyboard track layout tidied up.
- 2x12 IDC keyboard header added to keyboard side to support PS/2 or other keyboard adapters.
- Voltage rail circuits improved substantially.
- Right-angle tracks smoothed to 45 degree wherever possible.
