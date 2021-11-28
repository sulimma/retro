# ReTrOO - Register Transfer Object Oriented HDL

These are some ideas on how a believe a productive HDL at the register transfer level looks like.
Maybe I will write a transpiler to VHDL at some point.

The main objectives copared to VHDL are:
 - make constructs syntesizable that most vhdl implemnetations will not synthesize
 - make the following aspects more convenient than they are in VHDL
   - fixed point arithmetics
   - FSM
   - shift registers
   - RAM 
   - streams
 
 Constructs that can be efficiently synthesized shall be more conventient to write than aspects that are hard to synthesize.

