<h1 align="center">Koralyth Disassembler & Decompiler</h1>

This project is a result of countless hours of hard work and development. We ask that you do not claim this project as your own, and give credit where it is due.  

> **Note:** This project is licensed under the GNU General Public License v3.0.

If you'd like to compile your script, please refer to the `/compile` directory.

## Debug Mode

Turning on the `DEBUG` flag will slow down the decompilation process significantly.
- **Performance Impact:** 0.000406s -> 0.002075s, around 5x slower

The `DEBUG` flag is meant for development purposes only. Turn off before using in production.

## Issues
  
- ~~Does not show jump targets (e.g., if code has `goto [5]` but only has 3 instructions, it doesn't show `::5::` and its dism)~~ Fixed
- No type checking
- Does not handle variables kindly
