Hello

I decided to start a quite useless project. I want to write from scratch a Risc-V core and an assembler for this core. The goal is just for me to learn as much as I can about computer architecture and have fun. I will try to go as far as I can, but for now I will limit myself to a single core without pipeline running a fibonnaci.

This page is not some kind of documentation but just to keep a log of this journey.

## Chapter 1 - opensource tools
I want to use only opensource tools for this project. For the most part it is quite easy. I wanted to learn rust so the model and the assembler will be written in rust. The tricky part is to find a opensource SystemVerilog simulator. I can always use Vivado in last resort but I really want to find an opensource tools. After some research I found Icarus Verilog and Verilator. I want both my RTL and my testbench to be in SV so I decided to give Icarus Verilog a shot. It looks like it works fine with simple code useing always_ff and always_comb so hopefully I will be able to use it for my project. Otherwise I will use Vivado.


