# nes-mapper-sxrom
NES Mapper for MMC-X

MMC-X provides a flexible, extremely-large-ROM mapper using an FPGA, DRAM, and either low-capacity PRG RAM or large-capacity NAND.  Its purpose is to fit into the same cost as UnROM-512 (Mapper 30) with much larger capacity and a more-flexible window.

MMC-X provides audio output on NES Expansion Pin 6, requiring modification to get sound.  It supplies some audio extensions, notably VRC6.

This repository will include the specification, circuit board layout, FPGA implementation, and a mapper implementation for the Everdrive N8 and N8 Pro.
