# FISA (FLAME ISA)

Flame ISA is a on-going project made within 24 hours. This was a project for an exhibition.

### How to use it?

First, install these files as ZIP and extract them into your main directory.

Then make a new file. The file name does not matter, <b>BUT</b> the extension matters. The extension is `.fis`

## OPTIONAL

If you want you can add these the directory of these 2 executables into the Environment Variables!

### HOW TO RUN FILE

For a simple Demo:
```
START
MOV 1 20
SHOW 1 1
HLT
```

What this code does:
- `START` Should contain in every single file of `.fis`
- `MOV 1 20` Moves the value 20 to register 1.
- `SHOW 1 1` Show the value of the register 1 (the 1 after the show is to tell that your register contains integer data!)
- `HLT` Stops Execution.


Now Open up your terminal and go to your FISAAssembler and FISAInterpreter Directory. Your file should be in that specific directory. (If you have set these two executables in Environment Variables then switch to your code directory.)

Write:
`FISAAssembly.exe` (or `FISAAssembly` if you added to Environment variables) 

It will 2 questions, in the first one, just tell the name of your .fis file. In the second one just write the name (with extension `.faf`) and it will assemble your code.

Then run:
`FISAInterpreter.exe` (or `FISAInterpreter` if you added to Environment variables) 

It will ask for your assembled file (`.faf`) file! Just give it and see the output come!
