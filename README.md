Microbee Assembly Language Programming
The definitive book from the 80s

Here is every example from the book with modifications to make it compatible with maximum number of assemblers and cross compilers.

# List of working cross assembler for CP/M Z80 Assembler # 
All of these are working under macOS inside Sublime Text
- ***eZ80asm***- Z80 (16Bit) or eZ80 (24Bit) addressing - written for the Agon Light
- ***glass*** - requires java 8 to run (java -jar glass)
- ***pasmo***
- ***rasm*** (requires specific directives)
- ***sbasm*** (requires specific directives)
- ***sdasz80*** (requires specific directives) - weird directives for SEGA 8-Bit systems
- ***SjASMPlus***
- ***spasm-ng*** (requires specific directives)
- ***vasmz80*** (requires specific directives)
- ***z80asm*** - brew install z80asm
- ***z88dk-z80asm*** (requires specific directives)
- ***zasm***
- ***zmac***

# Z80 Cross Assemblers using BDOS calls #
## RunCPM ##
All Working except
- pasmo
- spasm-ng : issues
- sjasm
- rasm
- vasm

## uBEE512 ##
All working except spasm-ng
- pasmo
- spasm-ng : issues
- sjasm
- rasm
- vasm

# Native Assemblers and Disassemblers # 
- ***ASM*** The CP/M Assembler
- ***DIS - Super CP/M Z80 disassembler***
- ***MAC*** CP/M Macro Assembler
- ***Macro-80 aka M80*** (6502 code gen option via the .6502 directive)
- ***Mitek Z-80 Assembler***
- ***SLR 64180 Assembler***
- ***SLR Z-80 Assembler***
- ***SLR Z-80 Disassembler***
- ***Z-80 Macrom Assembler***
- ***2500 A.D. Software 8748 Cross Assember***
- ***2500 A.D. Software Z8 Cross Assembler***
- ***2500 A.D. Software Z8000 Cross Assembler***
- ***2500 A.D. Software 8080/Z-80 to Z8000 source code translator***

# Command Line Options #
- ***eZ80asm***
  - % eZ80asm -a0 -d hello.asm
- ***glass*** 
  - % java -jar glass-0.6.jar hello.asm
- ***pasmo***
  - % pasmo -v -d hello.asm hello.bin
- ***rasm*** 
  - rasm -map hello.asm hello
- ***sbasm*** 
- ***sdasz80*** 
- ***SjASMPlus***
- ***spasm-ng*** 
- ***vasmz80*** 
- ***z80asm***
  -  % z80asm -v -l -L hello.asm -o hello.bin
- ***z88dk-z80asm*** 
- ***zasm***
- ***zmac***
