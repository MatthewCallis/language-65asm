# v10.1.0

* Fix operator regex for ACME grammar (again) [#17](https://github.com/MatthewCallis/language-65asm/pull/17)

# v10.0.0

* Add support for asm6 assembler

# v9.0.0

Added https://github.com/georgjz as a collaborator 🎉

* Updated ACME Grammar (https://github.com/MatthewCallis/language-65asm/pull/11)
* Fix DASM & Merlin, add ASAR, improve CC65 (https://github.com/MatthewCallis/language-65asm/pull/10):
* Added a new grammar to support [Asar Assembler](https://github.com/RPGHacker/asar)
* Added SPC700 and SuperFX opcodes (extracted from the SNES cc65 grammar)
* DASM and Merlin should work now
* cc65
    * Added some missing commands and constants
    * Changed some scopes to improve readability
    * Added a new grammar for the linker config files ld65 uses
    * Updated the link in README.md
* Fixed hex numbers with a trailing h
* Add missing commands to WDC tools
