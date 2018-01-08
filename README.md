
Tutorial on how to get Hello World on pynq fpga.
1. import pynq hdf from the old github repo. (should be discontinued, 
https://github.com/Xilinx/PYNQ/tree/image_2017_01)
Do this by click on File, new -> application project

On target hardware, click new:
Import the HLF file. 

Now we have to program the Pynq fpga with the base.bit file, since 
the Hardware file is only an overlay (this is found on the xilinx tab on top)
The base.bit file you need is actually in the most recent github pynq edition
(master branch)


After Programming the fpga,
You are ready, 
Make sure in the sdk terminal you add com3 and com5 port with the highest baud rate
(115200) or something like that 
# pynq
