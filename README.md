

# Xilinx Zynq UltraScale+ MPSoC Series Core board ACU2CG、ACU3EG、ACU4EV、ACU5EV

***

## Core board Introduction


### Peripheral and memory chip

Five Micron DDR4 chips  (four for ACU2CG) are used, in which four DDR4 chips are mounted on the PS side, forming a 64-bit data bus bandwidth and 4GB capacity. One piece is mounted on the PL side (the PL side of ACU2CG is not mounted), which is 16-bit data bus width and 1GB capacity. The maximum operating speed of DDR4 SDRAM at PS end can reach 1200MHz (data rate 2400Mbps), and the maximum operating speed of DDR4 SDRAM at PL end can reach 1066MHz (data rate 2132Mbps). In addition, a 256MBit QSPI FLASH and 8GB eMMC FLASH chip are also integrated on the core board for starting storage configuration and system files. In order to connect with the backplane, the four board-to-board connectors of this core board extend the USB2.0 interface, Gigabit Ethernet interface, SD card interface and other remaining MIO ports at the PS end; 4 pairs of PS MGT high-speed transceiver interfaces have also been extended; As well as almost all IO ports at the PL end, the wiring from the chip to the interface has been processed with equal length and difference, and the core board size is only 80 * 60 (mm)

### Key Features

| name of core board |  ACU2CG              | ACU3EG              | ACU4EV            |  ACU5EV            |
|--------------------|----------------------|---------------------|-------------------|--------------------|
| ZYNQ               |  XCZU2CG-1SFVC784I   |  XCZU3EG-1SFVC784I  | XCZU4EV-1SFVC784I | XCZU5EV-2SFVC784I  |
| GPU+VCU            | no                   | no                  | yes               | yes                |
| size               | 80x60mm              | 80x60mm             | 80x60mm           | 80x60mm            |
| DDR4               |  2GB(PS)             |  2GB(PS)512MB(PL)   |  2GB(PS)512MB(PL) |  2GB(PS)512MB(PL)  |
| QSPI FLASH         |  32MB                |  32MB               |  32MB             |  32MB              |
| EMMC Flash         |  8GB                 |  8GB                |  8GB              |  8GB               |
| voltage            | 12V                  | 12V                 | 12V               | 12V                |
| connectors(b2b)    | 4x120pins            | 4x120pins           | 4x120pins         | 4x120pins          |
| Logic Cells        | 103K                 | 154K                | 192K              | 256.2K             |
| flip-flops         | 94K                  |  141K               |  176K             | 234.24K            |
| LUTs               | 47K                  |  71K                | 71K               | 117.12K            |
| Block RAM          | 5.3Mb                | 9.4Mb               | 20.6Mb            |  23.1Mb            |
| CMTs               | 3                    | 3                   | 4                 | 4                  |
| DSP                | 240                  | 360                 | 728               | 1248               |
| VCU                |                      |                     | 1                 | 1                  |
| PCIE3.0            |                      |                     | 2                 | 2                  |
| GTH 12.5Gb/s       |                      |                     | 4                 | 4                  |


***

## Official Website

<https://www.alinx.com/en>





