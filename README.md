# Guide for Debugging with ChipScope remotely 

Here is a link to the official Xilinx's documentation, which provides more detail. This tutorial is designed to walk you through the steps visually, and provide you a quick way to setup System ILAs in HLS. 
Possibly in the future a Verilog/VHDL version will be created. 

## Installation 

```
git clone https://github.com/pyuvaraj37/hls_catch22.git
cd hls_catch22
```

## Adding ChipScope
We can add the \[debug\] header to our configuration file and add statements to monitor ports of our kernel. 

```
[debug]
chipscope=krnl_1:input
chipscope=krnl_1:output
```