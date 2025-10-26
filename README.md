MIC-1 is a CPU architecture invented originally by Andrew Tanenbaum. 
It is mainly devised for IJVM, which is an instruction set architecture, mostly a subset for an assembly language (JVM).

Due to inability to run such architecture, an emulator was created by the University of Duisburg Essen for educational purposes:
https://vs-ude.github.io/mic-1-toolbox/

The JSON files attached are a few examples I created to demonstrate how it functions with each instruction:
11 - Simple Addition Loop
21- Addition of a 2D Vector (10,4) with (3,2) to give (13,6) on the memory stack as output using the macro program.
223 - Same as 21, but using the microcode instruction set, the function name is IVECADD.
312 - Usage of microcode to create a function called IGCD to find the greatest common divisor between two numbers.
