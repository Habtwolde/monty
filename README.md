# 0x19. C - Stacks, Queues - LIFO, FIFO

# The Monty language

Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.`monty` is an interpreter of Monty ByteCodes files, which is a scripting language just like Python.

This is a language that contains specific instructions to manipulate data information (stacks or queues), where each instruction (*called opcode*) is sended per line. Files which contains Monty byte codes usually have the `.m` extension.

## Features
### Opcodes
`monty` executes the following opcodes:

| Opcode | Description |
| -------- | ----------- |
| `push` | Pushes element to the stack |
| `pall` | Prints all the values on the stack |
| `pint` | Prints the value at the top of the stack |
| `pop` | Removes the top element of the stack |
| `swap` | Swaps the top two elements of the stack |
| `queue` | Sets the format of the data to a queue (FIFO) |
| `stack` | Sets the format of the data to a stack (LIFO) |
| `nop` | Doesn't do anything |
| `add` | Adds the top two elements of the stack |
| `sub` | Subtract the top element of the stack from the second top element of the stack |
| `mul` | Multiplie the second top element of the stack with the top element of the stack |
| `div` | Divide the second top element of the stack by the top element of the stack |
| `mod` | Compute the rest of the division of the second top element of the stack by the top element of the stack |
| `pchar` | Print the char at the top of the stack |
| `pstr` | Print the string starting at the top of the stack |
| `rotl` | Rotate the stack to the top |
| `rotr` | Rotate the stack to the bottom |

## Authors
* Habtamu Wolde:- [GitHub](https://github.com/Habtwolde)
* Nitsuhe Fenta:- [GitHub](https://github.com/Nitsuhe)
