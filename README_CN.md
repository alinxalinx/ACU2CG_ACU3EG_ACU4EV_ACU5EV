# Xilinx Zynq UltraScale+ MPSoC 系列核心板ACU2CG、ACU3EG、ACU4EV、ACU5EV

***

## 核心板介绍


### 外设接口以及存储芯片

使用了 5 片 Micron 的 DDR4 芯片 (ACU2CG为4片),其中 PS 端挂载 4 片 DDR4，组成 64 位数据总线带宽和 4GB 的容量。PL 端挂载 1 片(ACU2CG的PL端没有挂载)，为 16 位的数据总线宽度和 1GB 的容量。PS 端的 DDR4 SDRAM 的最高运行速度可达 1200MHz(数据速率 2400Mbps)， PL 端的 DDR4 SDRAM 的最高运行速度可达 1066MHz(数据速率 2132Mbps)。另外核心板 上也集成了 1 片 256MBit 大小的 QSPI FLASH 和 8GB 大小的 eMMC FLASH 芯片，用于启 动存储配置和系统文件。 为了和底板连接，这款核心板的 4 个板对板连接器扩展出了 PS 端的 USB2.0 接口，千兆 以太网接口，SD 卡接口及其它剩余的 MIO 口；也扩展出了 4 对 PS MGT 高速收发器接口； 以及 PL 端的几乎所有 IO 口,芯片到接口之间 走线做了等长和差分处理，并且核心板尺寸仅为 80*60（mm）

### 主要特性

| 核心板型号         |  ACU2CG              | ACU3EG              | ACU4EV            |  ACU5EV            |
|--------------------|----------------------|---------------------|-------------------|--------------------|
| 主芯片             |  XCZU2CG-1SFVC784I   |  XCZU3EG-1SFVC784I  | XCZU4EV-1SFVC784I | XCZU5EV-2SFVC784I  |
| GPU+VCU            | no                   | no                  | yes               | yes                |
| size               | 80x60mm              | 80x60mm             | 80x60mm           | 80x60mm            |
| DDR4               |  2GB(PS)             |  2GB(PS)512MB(PL)   |  2GB(PS)512MB(PL) |  2GB(PS)512MB(PL)  |
| QSPI FLASH         |  32MB                |  32MB               |  32MB             |  32MB              |
| EMMC Flash         |  8GB                 |  8GB                |  8GB              |  8GB               |
| 电压               | 12V                  | 12V                 | 12V               | 12V                |
| 连接器(板对板)     | 4x120pins            | 4x120pins           | 4x120pins         | 4x120pins          |
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

## 相关载板开发板

1. https://github.com/alinxalinx/AXU2CG-E_AXU3EG_AXU4EV-E_AXU5EV-E
2. https://github.com/alinxalinx/AXU4EV-P_AXU5EV-P

## 官方网站

<https://www.alinx.com>



