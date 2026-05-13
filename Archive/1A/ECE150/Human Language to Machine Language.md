---
tags:
  - "#review"
  - "#flashcards"
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
---
*Key Concepts:*
___

- Programming languages, such as cpp, python, go, js, etc, are purely ==abstraction layers intended for humans to be able to interact with machines==
	- Machines work on a strict set of ==instruction sets==, which include rudimentary operations such as:
		- Goto
		- Add
		- Multiply
	- These intruction sets are standardized, such as
		- x86
		- ARM
		- MIPS
	- Each instruction set has its own ==benefits and disadvantages==
		- There is a never ending war fueled by spite and pretentiousness between which instruction set is the best. 

- Compilers and Interpreters are tools which convert the human-written programming language to machine code. 
	- Compilers: ==Convert the entirety of the program before it is executed, allowing for faster and more robust programs==
		- The compiler outputs ==object code==, which is the binary executable for a single file only. This becomes a problem when there are multiple files or dependencies for a system of files. See ==linkers==
		- Oftentimes used in Real time systems, where reliability and speed are key
	- Interpreters: ==Convert the code line by line as it is executed, allowing for easier debugging and sometimes ease of development==

- Linkers are tools which take object code and connect them to each other and external dependencies / libraries

- The workflow of C++ looks like so:
	- ==C++ -> Compiler -> Linker==

*Examples (Excluding inline examples)* 
___

*Significant Theorems:*
___

*Respective Proofs*
___

*Common Mistakes:*
___

*Terms and Definitions:*
___

