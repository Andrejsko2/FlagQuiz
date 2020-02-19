# FlagQuiz
Altera Quartus Project for Fundamentals of Computer Engineering subject

This is a game for two players. The goal of the game is to guess more country flags than your opponent.
Each player has his own FPGA board and a keyboard. As soon as the flag comes up on the screen, players can start typing the name of the corresponding country.
This project uses both VGA and PS/2 protocols for displaying flags and registering keyboard input, respectively.

TEHNICAL:
There are two Quartus projects. "Master" shows flags on the screen, while "2nd" only transmits word input to the "Master" board. Two projects are compiled independently and the boards are connected to each other using extension headers.
