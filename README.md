* Addressing modes in computer organization refer to the methods by which the CPU accesses operands (data or instructions) in memory or registers during program execution.
* The different ways for specifying the locations of instruction operands are known as addressing modes.

RISC-Type Addressing Modes:
* Immediate
* Register
* Absolute
* Register Indirect
* Index and Base with Index 

RISC-Type addressing modes
*Immediate mode:
Definition: In immediate mode,the operand’s value is directly specified within the instruction itself.
Example: consider the instruction ADD R1, #10.
* ADD is the operation to be performed.
* R1 is the destination register.
* #10 is the immediate value to be added to the content of register R1.

* Register Mode:
Definition: Register mode involves specifying operands stored in registers within the instruction.
  
  
  
Example: consider the instruction ADD R1, R2
* ADD is the operation to be performed.
* R1 is the destination register.
* R2 is the source register whose content will be added to the content of register R1.

* Absolute Mode:
Definition: Absolute mode accesses operands directly from memory using a memory address provided within the instruction.
  
  
  
Example: Consider the instruction LOAD R1,  0*1000
* LOAD is the operation to be performed.
* R1 is the destination register.
* 0*1000 is the memory address from which the content will be loaded into register R1.

* Register Indirect Mode:
Definition: In register indirect mode,the operand’s memory address is specified indirectly through a register or a memory location.
  
  
  
Example: Consider the instruction LOAD R1, (R2)
* LOAD is the operation to be performed.
* R1 is the destination register where the content will be loaded.
* (R2) indicates that the memory address of the operand is stored in register R2.

* Index Mode:
Definition: Index mode adds an offset to a base address stored in a register to access memory.

  
  
Example: Consider the instruction LOAD R1, (R2 + 4).
* LOAD is the operation to be performed.
* R1 is the destination register where the content will be loaded.
*(R2 + 4) indicates that the memory address of the operand is obtained by adding 4 to the content of register R2.

* Base with Index Mode:
Definition: Base with index mode employs a base register and an offset to access memory locations.

Example: Consider the instruction LOAD R1, (R2 + 4).
* LOAD is the operation to be performed.
* R1 is the destination register where the content will be loaded.
* (R2 + 4) indicates that the memory address of the operand is obtained by adding 4 to the content of register R2.
