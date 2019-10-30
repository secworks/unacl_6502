# unacl_6502
Test implementation/port of the uNaCl library to the 6502 cpu.


## Status
Not completed. Does not work. **Do. Not. Use.**


## Introduction
The c64 and other MOS 6502 based machines lacks good, modern crypto such
as [NaCl](https://nacl.cr.yp.to/). [AVRNacl, also known as uNaCL](https://munacl.cryptojedi.org/atmega.shtml) is a
port of NaCl to the 8-bit RISC based MCU AVR from Atmel/Lattice. The
port was [created by Michael Hutter and Peter
Schwabe](https://cryptojedi.org/papers/avrnacl-20130220.pdf) (PDF).

This is an attempt at porting the AVR port to the MOS 6502 processor. It
might turn out to be really bad.
