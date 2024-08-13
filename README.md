# SIC ASSEMBLER

## Description:
- An assembler is a translator, that translates an assembler program into a conventional machine language program. Basically, the assembler goes through the program one line at a time and generates machine code for that instruction.

## Tools:
- Visual Studio Code (VS Code)

## Language Used:
- High level programming language used: C++

## Implementation:

- Input source program: Copying of set of elements from one array to another array.
- There are 2 set of programs.
	1. sp_pass_1 for pass 1.
	2. sp_pass_2 for pass 2.

- sp_pass_1 : Takes source program (input1 file) and optab as input files.
	      Then generates symtab and output.
	      Symtab contains labels and corresponding addresses.
	      Output contains source program with location counter. Output acts as an intermediate file.

- sp_pass_2 : Uses output file and generates object code (in objectcode file).

## Note:
- ** is used for tab space in source program (input1 file)
