## Interpreter for Monty ByteCode files
Files containing Monty byte codes usually have the <code>.m</code> extension. Most of the industry uses this standard but it is not required by the specification of the language. Monty ByteCode contains opcodes specific to Monty. This is an interpreter for these special opcodes: `push`, `pall`, `pint`, `pop`, `swap`, `swap`, `add`, `nop`

### Description
* bytecode folder ----- holds Monty ByteCode files
* monty.h ------------- holds all function prototypes for interpreter
* main.c -------------- entry into program

### Usage
Usage: ./monty [filename]
```
$ git clone https://github.com/Jinnie506/monty
$ cd monty
$ gcc -Wall -Werror -Wextra -pedantic *.c -o monty
$ ./monty bytecodes/000.m
```

### Environment
* Language: C (version C89)
* OS: Ubuntu 14.04 LTS
* Compiler: gcc 4.8.4
