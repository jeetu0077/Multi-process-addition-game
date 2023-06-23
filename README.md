# Multi-process-addition-game

The objective of this project is to demonstrate interprocess synchronization and concurrency by playing a game of addition in which multiple process modify a variable in the shared memory region until one process wins. 
The game: A process enters the game and adds two numbers present in the shared memory. If the sum of addition is greater than a predefined variable M then the process declares itself the winner and exits. Else the process swaps the lesser of two numbers with the value of sum and exits to play the game again. All processes play the game concurrently until a winner is declared.
