# Compile 02 Project USTHB M1 SE

This is the English version of the README. For French, please see [README_FR.md](./README_FR.md).

## Description 

> The purpose of this project is to create a mini-compiler by going through the various compilation phases, namely lexical analysis using the FLEX tool and syntactic-semantic analysis using the BISON tool, for the 'Lang' language. The structure and details of the project are available in the statement

## Tools and Development Environment
<div align="center">
       <b> Flex </b>
    -- <b> Bison </b>
    -- <b> C programming language </b>
    -- <b> Command Prompt (CMD) or a code editor (VS Code, for example) </b>
</div>

## How to make the program work (execute) ?
After installing all the necessary tools, to execute the program, follow these steps:
- Click on the Windows Start button. In the search area, type 'cmd' 
- Navigate to the folder where the files are located and type these commands
  - `flex PartieLex.l`
  - `bison -d PartieSyntax.y`
  - `gcc lex.yy.c PartieSyntax.tab.c  -lfl -ly -o test`
  - `test  < MonExemple.txt` 
- Alternatively, instead of typing all these commands, you can directly enter  
  - `comande.bat` , The execution will start, and the result will be displayed afterward

## Routines defined in the semantic part
- Double declaration
- Undeclared variables
- Array size overflow
- Forbidden change of value for a constant
- Division by 0
- Type incompatibility
- Array size must be > 0
- Number of formatting signs
- Quadruple routines (IF, WHILE, DO WHILE)
- .......................


<table align="center">
  <tr>
    <th>
    📝 We can add the missing parts to this project: Code Optimization and Object Code Generation (according to the syntax of the 8086 assembler)
    </th>
  </tr>
</table>
