## Introduction to Addressing modes in Computer Organization:
Addressing in computer organization refers to the methods by which an instruction within a program accesses data stored in the system. When an instruction is executed, the addressing mode determines where the operand for the instruction is located.

**OPCODE AND OPERAND:**

Opcodes and operands are two key components of machine language instructions that specify which operations the computer's CPU should do. 

**Opcode (operation code):**

The opcode is a component of a machine language instruction that specifies the operation that will be executed. 

**Operand :**

The operand is the portion of the machine instruction that defines the data or addresses of the data on which the operation should be performed.


**Example of Opcode and Operand:**

*SUB R1,R2,R3*

*Opcode:* 
ADD – Tells the CPU to subract the contents of two registers.

*Operands:* 
R1, R2, R3 – In this case, R2 and R3 are the source operands whose values are to be subracted, and R1 is the destination operand where the result of the subtraction will be stored.

## Types of Addressing modes:

**1.Stack addressing mode:**

The operand is contained at the top of the stack.

*Eg:*
SUB - This simply pops out two operand contained at the top of the stack,performs operation and stores the result at the top of the stack.

**2.Immediate addressing mode:**

The operand is directly specified in the instruction itself.

*Eg:*
Sub 10 - Will subract the accumulator value by 10.

**3.Direct addressing mode:**

The address field of the instruction contains the direct address of the memory location where the data is stored.

*Eg:*
ADD X -Here X holds the effective address of the operand.

**4.Indirect addressing mode:**

The address field of the instruction holds the address of the memory location which holds the effective address of operand.

*Eg:*
Add y - Here Y holds the address of memory location which has the address of the operand.

**5.Register addressing mode:**

Here operand is stored in Register set.
There is no need to refer the memory loaction to fetch the address.In instruction set it holds the register set which has the operand.

*Eg :*
Add R - Here R (resgister set) holds the operand.

**6.Register indirect addressing mode:**

In the instruction set it holds the cpu register that contain the effective address of the operand.

*Eg :*
Add S - Here S holds the effective address of the operand.
