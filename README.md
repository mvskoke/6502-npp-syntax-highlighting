# 6502-npp-syntax-highlighting
My custom user-defined language (UDL) syntax highlightings for 6502 assembly for notepad++

All UDLs **ARE COMPATIBLE** with 65C02 instructions.

I used the npp++ syntax file that came with the 64tass source code as a starter: [64tass source](https://sourceforge.net/projects/tass64/)

I don't understand half the things in the .xml file.
I simply guessed and experimented with it until things worked

# Variants
There are three variants:

* 6502-sublime
	* Meant to be used with notepad++'s monokai theme. Mimics sublime text.
* 6502asm-custom
	* My custom UDL for 6502 assembly. Basically 6502-sublime, but light mode.
* 6502-x86colors
	* Mimics notepad++'s syntax highlighting for x86 assembly.

My primary purpose was to make the UDLs look their nicest with "Courier" font for maximum immersion. But "Courier New" looks alright too.

# How to use
First, download the .xml files that you want.

To use, open notepad++, Language>User Defined Language>Define Your Language...

In the pop-up menu, click the "Import" button near the top, and select the .xml file from wherever you saved it.

You will have to restart notepad++ before it shows up in the Language drop-down menu.

To use monokai theme in notepad++, go to Settings>Style Configurator...>Select theme: and choose monokai from the drop-down menu.
