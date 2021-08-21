# [Compukit UK101](https://en.wikipedia.org/wiki/Compukit_UK101) for [MiSTer](https://github.com/MiSTer-devel/Main_MiSTer/wiki)

Port by [danielb0](https://github.com/danielb0)

## Description

This core is a port of [Grant Searle's UK101 project](http://searle.x10host.com/uk101FPGA/index.html) to MiSTer FPGA. It is a reconstruction of a kit computer from the late 1970s, which was based on a 6502 processor that ran at 1 MHz and originally came equipped with 8Kb of RAM.

This core includes some enhancements which Grant added to his own project such as the 64x32 display and a 32Kb RAM expansion.

Saving and loading of Basic programs can be done via the UART, at 9600 baud. Instructions for this can be found on Grant's page and in the [Compukit UK101 manual](http://uk101.sourceforge.net/docs/pdf/manual.pdf).

### Licenses 

#### Grant Searle's original license:
```
By downloading these files you must agree to the following:
The original copyright owners of ROM contents are respectfully acknowledged.
Use of the contents of any file within your own projects is permitted freely, but any publishing of material containing whole or part of any file distributed here, or derived from the work that I have done here will contain an acknowledgement back to myself, Grant Searle, and a link back to this page.
Any file published or distributed that contains all or part of any file from this page must be made available free of charge.
```
#### Cray Ze Ape's license:

`Unrestricted release - do with it as you see fit.`

### Original sources

#### Grant Searle's original site

http://searle.x10host.com/uk101FPGA/index.html

#### VGA interface by Cray Ze Ape:

https://github.com/douggilliland/MultiComp/tree/master/MultiComp%20(VHDL%20Template)/Components/VGA/VGA_CraZeApe

### UK101 Manual

http://uk101.sourceforge.net/docs/pdf/manual.pdf

