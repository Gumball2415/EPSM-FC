# EPSM-FC

Expansion Port Sound Module for the Famicom

<img src="EPSM YMF288 Modular Famicom Horizontal/docs/EPSM YMF288 Modular Famicom Horizontal.png" style="max-width:80%;" />

## About

Work in progress!!

This is a version of the EPSM ported for use with the Famicom.

The challenge with the Famicom version is that the device no longer has access
to the extra control signals on the NES expansion port. Most relevant, OUT1,
CPU_A15, and all the EXP pins. This project aims to solve this using extra logic
that can recreate the necessary signals for addressing the EPSM.

## License

This design is licensed under the TAPR Open Hardware License.\
For resale, please contact Pierre Althinsson (Perkka).

Original EPSM is Copyright (C) 2021-2025 Pierre Althinson.\
EPSM-FC is Copyright (C) 2022-2025 Persune.

## Usage

- [NESDev wiki](https://www.nesdev.org/wiki/Expansion_Port_Sound_Module)
- Also see [the original EPSM repo](https://github.com/Perkka2/EPSM/)
