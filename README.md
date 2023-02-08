# 32bit_pipline_cpu

32 bit pipelined RISC CPU created using logisim.<br />
support data hazards and control hazards.<br /><br/>
![alt text](https://github.com/HadiSormeyli/32bit_pipline_cpu/blob/main/img/32_pipline_cpu.png)

<br />
<h1>Instruction formats</h1> 
There is thress instruction formats,The formats
use a single word of 32 bits. This longer word length is needed to hold realistic
address values, since additional instruction words for holding addresses are difficult
to accommodate in the RISC CPU. The first format specifies three registers. The two
registers addressed by the 5-bit source register fields SA and SB contain the two
operands. The third register, addressed by a 5-bit destination register field DR, specifies
the register location for the result. A 7-bit OPCODE provides for a maximum of
128 operations.<br/><br/>
<p align="center">
  <img src="https://github.com/HadiSormeyli/32bit_pipline_cpu/blob/main/img/instruction_formats.png" title="instruction formats">
</p>


<br />
<h1>Opcodes</h1> 
<br />
![alt text](https://github.com/HadiSormeyli/32bit_pipline_cpu/blob/main/img/opcodes.png)
<br /><br/>
As an example for instruction:<br/>
MOVA R1,R3;<br/>
the binary instruction code will be 10000000000100011000000000000000.
