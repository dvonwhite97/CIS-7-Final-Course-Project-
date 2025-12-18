General Project Summary:
Authors: Dvon White
A. Core Project Direction
The objective of this project was to develop a console-based Blackjack simulation written entirely in C++, capable of modeling a complete round of play using standard Blackjack rules.
An optional HTML/JavaScript graphical user interface (GUI) was included to display the program’s output for demonstration purposes, without modifying the core logic.
B: Prototype Integration Framework
To validate GUI feasibility, a prototype was developed where the C++ program writes results to an output.txt file, which the HTML interface reads using JavaScript.
This confirmed that the C++ logic and GUI can operate independently while sharing data through file I/O.
C: Development Environment Configuration
A stable development environment was established using MSYS2 GCC/G++, gdb, and Visual Studio Code.
Execution path issues and debugger configuration problems were resolved to ensure consistent file access between the compiled C++ program and the HTML Live Server.
D: Program Design Overview
The program logic is modular and follows standard Blackjack rules:
Deck creation and shuffling, Initial deal, Player hit/stand decisions, Dealer automated behavior, Final comparison and result determination, Game outcomes and statistics are written to the console and output.txt.
E. Algorithm and Flow Design
The control flow follows a structured sequence:
Start → Initialize Deck → Deal Cards → Blackjack Check → Player Turn → Dealer Turn → Compare Totals → Display Results → End or Replay
This structure was formalized using a flowchart and pseudocode prior to implementation.
Date Published: 12/17/25 (V1 dated 11/21/25)
INSTRUCTIONS: 1. Run program: Blackjack Game will intitiate immediately and display both player and dealer hands.
2. Play game! 3. Win or lose/Program terminates itself after round; Must run again to play again. 
