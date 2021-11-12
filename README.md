# oPoW Hardware

The repository contains the design from for the [Optical Proof of Work](https://arxiv.org/abs/1911.05193) paper.

Designed by [SiEPIC Kits](https://www.siepic.com/). Please contant Mustafa Hammood (mustafa@siepic.com) for further design details.

Please read the [documentation here](siepic_powx_hardware.pdf) for details about the content of this repository. Please note that reading that document may not be fully clear to the reader since many of the information about the chip, its fabrication process, and design details are not publicly available due to confidentially agreements with the manufacturing foundries and their partners.

# What's in the repository?

- GDS of the chip: contains the actual design of the chip fabricated. (layer numbers are dummy numbers to preserve manufacturing foudnry confidentiality...)
- Gerber files for the sub systems used in the testing of the chip such as the TIA board, interposer board, and electronics control interposer boards.

As the designer of the TIA board, i highly recommend you redesign the board personally :) There's much room for improvement and the design.

# Coming soon

-The GDS provided here doesn't allow for completely arbitrary matrix mults (not enough heater controlled MZIs in the mesh). We'll upload a newer 8x8 multiplier design shortly that can perform any arbitrary unitary matrix. 
