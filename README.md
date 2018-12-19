# 65816/65C816/65802/6502/65C02 Assembly Language Support in Atom

Adds syntax highlighting to 65816/65C816/65802/6502/65C02 files in Atom, with extra support for various compilers:

 - [ACME Crossassembler](https://sourceforge.net/projects/acme-crossass/)
 - [Asar SNES Assembler](https://github.com/RPGHacker/asar)
 - [ASM6f](https://github.com/freem/asm6f) (support for NES emulator Mesen)
 - [cc65 (SNES Syntax: 65816, SPC700, SuperFX)](https://github.com/cc65/cc65)
 - [DASM](http://dasm-dillon.sourceforge.net/) (6502)
 - [EDASM](https://archive.org/details/EDASM-ProDOS_Assembler_Tools_Manual)
 - [Merlin](http://en.wikipedia.org/wiki/Merlin_(assembler))
 - [MPW IIgs Assembler](http://store.16sector.com/index.php?main_page=product_info&products_id=24)
 - [NinjaForce Assembler](http://www.ninjaforce.com/html/products_nf_assembler.html)
 - [ORCA/M](http://www.byteworks.us/Byte_Works/Products.html)
 - [WLA-DX](http://www.villehelin.com/wla.html)
 - [WTCTools by Western Design Center](http://westerndesigncenter.com/wdc/tools.cfm)

Originally [converted](http://atom.io/docs/latest/converting-a-text-mate-bundle)
from the various other TextMate bundles:

 - [6502asm-tmbundle](https://github.com/adamv/6502asm-tmbundle)
 - [65816.tmbundle](https://github.com/ksherlock/65816.tmbundle)

Contributions are greatly appreciated! Please fork this repository and open a
pull request to add snippets, make grammar tweaks, etc.

# Installation

In atom, press `ctrl+shift+p` and enter `install package`, then type `language-65asm` into the search bar and hit install.

#### OR

Run `apm install language-65asm` in a terminal.

To add automatic syntax highlighting to a set of file extensions, add this to your
config.cson (`ctrl+shift+p` -> config):

```
"*":
  core:
    customFileTypes: {
      "source.assembly.6502.cc65": [
        "asm"
        "inc"
      ]
    }
```

See last line in grammar files for names.

# Contributors

- [Matthew Callis](https://github.com/MatthewCallis)
- [Matt Tuttle](https://github.com/MattTuttle)
- [Tommy Savaria](https://github.com/NewLunarFire)
- [ARM9](https://github.com/ARM9)
- [georgjz](https://github.com/georgjz)
- [GoDot](http://www.godot64.de/)
