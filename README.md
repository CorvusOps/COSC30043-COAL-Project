# COSC30043-COAL-Project
A Project in partial fulfillment for COMP 30043: Computer Organization and Assembly Language 

# The Guessing Game
The Guessing Game is a simple assembly program that let its users try the game of guessing a number between 1 – 100.

## Project Scope 
The purpose of this project is to provide the user a simple form of entertainment through a simple game with the use of NASM assembler. This project also serves as a way for the programmers to implement their knowledge in assembly language through our subject  Computer Organization and Assembly Language. Through this project we will better understand the capabilities of assembly language as we develop the guessing game.
### Describe the work to be accomplished
 - To create a program using the NASM assembler that provides the user a simple guessing game.
 - To be able to  create functions that would help implement rules on the guessing	game. 
 - To be able to randomize numbers for varying guessing values each try.

# Instruction Manual
## Assembling and running the program
- Open terminal. In our case, we have used Ubuntu. 
- Assemble the program.
    - In the terminal, enter nasm –f elf guess.asm
- Once an object file has been created, link it with the executable file
    - In the terminal, enter ld -m elf_i386 -s -o guess guess.o
- Execute the program by typing ./guess
## Playing the Game
- You will be prompted to enter a number.
- Once you have guessed the correct number, the program will end.
  - However, if not, you will be prompted to guess again until the 6th try if you still haven’t guessed correctly.




