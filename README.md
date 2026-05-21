# CSE420 Compiler Design Sessional

This repository contains the complete implementation of a mini compiler for a subset of the C programming language developed for the CSE420 Compiler Design Sessional course.

## Implemented Labs

### Lab 1 – Lexical & Syntax Analyzer

* Implemented lexical analysis using Flex (Lex)
* Implemented syntax analysis using Bison (Yacc)
* Generated tokens for a subset of C language
* Performed syntax validation

### Lab 2 – Symbol Table

* Implemented symbol table using hash table
* Managed nested scopes
* Supported insert, delete, and lookup operations

### Lab 3 – Semantic Analysis

* Performed semantic error checking
* Type mismatch detection
* Variable and function validation

### Lab 4 – Intermediate Code Generation

* Constructed Abstract Syntax Tree (AST)
* Generated Three Address Code (TAC)
* Built intermediate representation of source code

## Technologies Used

* C++
* Flex (Lex)
* Bison (Yacc)

## Project Structure

```bash
CSE420-Compiler-Sessional/
│
├── Lab-1-Lexical-Analyzer/
├── Lab-2-Symbol-Table/
├── Lab-3-Semantic-Analysis/
└── Lab-4-Code-Generation/
```

## How to Run

### Compile

```bash
flex lexer.l
bison -d parser.y
g++ lex.yy.c parser.tab.c -o compiler
```

### Run

```bash
./compiler input.c
```

## Course Information

Course: CSE420 – Compiler Design Sessional
Department of Computer Science and Engineering

## Author

SAYEM AFRIDI
