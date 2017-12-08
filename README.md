# AXI DMA with SPI interrupts

This repository included an example of how to use AXI DMA IP core design and xilinx bare-metal library.

It is using DMA in scatter gather mode using interrupts. To create a loopback AXI FIFO is being used also in FPGA design.

# Design

I am using Shared peripheral interrups (SPI) wth a concat in this design. 

![](images/axi-dma-irqs.png?raw=true)

# Versions

Vivado version for this design is 2014.4.

# Target platform

Target platform is zynq 7000 zedboard.

# Compile and run sample

Just use Xilinx SDK with the project is included in this repo and there should not be any problem to make a correct deploy.

Enjoy!

Thanks to fpgadeveloper and xilinx samples for inspiration.
