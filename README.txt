////////////////////////////////////////////////////////////////////////8-bit adder using module instantiation\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\



 => All codes are in .v file and they are coded using ALTERA MODELSIM.
 => First of all NAND gate is made using mixed type modelling of behavioral and gate level modelling.
	
 => NAND gate is a universal gate so using nand gate xor gate module is made by method of module instantiation and circuit defining.

 => Then using 2 NAND gates an AND gate is made, and using AND gate and XOR gate a half adder is made.
 => Similarly using half adder, a full adder, 4 bit adder is made and finally using 2 4-bit adder an 8 bit adder is made using module instantiation.


 => testbench of final 8-bit adder is also included.

 => **IMPORTANT - values of input and carryin is in decimal form I would suggest to change to values to binary as this is an adder not summer so it will not show
                  sum of two decimal but rather it will show binary sum of two 8 bit numbers with carryout.

 => Import all files to Modelsim or Xilinx to run simulation waveform or to see schematics.
 
 # Project file is also added as a pdf file.

