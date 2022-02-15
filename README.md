# Amaranth+Coriolis Test SoC

This is a submission of a test SoC for MPW4 built from https://github.com/ChipFlow/mpw4

It contains:
 - Minerva RV32IM CPU
 - 512 bytes SRAM
 - (Q)SPI flash for code and data memory using `spimemio` from picosoc
 - HyperRAM for RAM extension using a derivative of `litehyperbus`
 - 8-bit GPIO
 - UART, timer, and interrupt controller


Built using:
 - Amaranth
 - Yosys+ABC
 - [Coriolis](https://gitlab.lip6.fr/vlsi-eda/coriolis) for PnR; with [PDKMaster](https://gitlab.com/Chips4Makers/PDKMaster) and [flexcell](https://gitlab.com/Chips4Makers/c4m-flexcell) used in place of the standard sky130 cells.
