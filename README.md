# Project-2
This project was created in a CS-231 course I took as a freshman at Jacksonville State University. In this course we studied the basics of C++. The project was created at the end of the course. It was meant to act as a summary and final implementation of the C++ skills we had acquired during our time in the course.
This project was called Sea Battle. It was designed after the well known game battle ship. The purpose of the game was to sink the opponents ships. By sinking the opponents ship, you win the game! This game had lots of different variables to take into consideration. The first one was deciding which player the user wanted to be. This is a two player game. The computer is the other player. The player needed to decide which player he/she wanted to be in order to assign the grid to that player. The user then needed to decide if he/she wanted to go first or second at the beginning of the game. Two grids are then printed to the screen. The primary grid is the users grid. It displays five types of ships, each different in length, but 9 ships in total. The tracking grid that is printed to the screen is to help the user keep track of the opponents ships that he/she sank or parts of the ships that he/she hit. The tracking grid is updated after every hit or sink. The program keeps track of how many ships are left on each grid. The goal is for either user to sink all of the ships of his/her opponent. 
This project includes a total of five files. One file is the main file, which is needed in any C++ program. It is primarily used to call the declared functions and to run the game. It includes several loops and if then else statements. These are used primarily to update the game and keep the game running if there is not a winner yet. One other file is a grid.cpp file and a corresponding grid.h file. The grid.h file included the creation of the grid class. This class was created to manage both primary and tracking grids in the Sea Battle game. The grid.cpp file included the implementation of the grid class in the Sea Battle game. It included the use of constructors. This file did everything from deploying the ships into the grid, to setting the cells of the grid, to returning the contents of a cell, to printing the grid names and contents to standard output. 
The project also included a util.h file and a corresponding util.cpp file. The util.h file contained several useful utility functions for the Sea Battle game. It also introduced the concept of Structs, which was used in the implementation of the cells of the grids. The util.cpp file was the implementation of the utility functions declared in the util.h file. 
Upon completion of this project, we had just studied a new concept: classes. This project's main focus was the creation of classes and using constructors to implement our classes. This project reemphasized the importance of classes in complex projects such as this one. At the beginning, the concept of classes was a very hard concept for me to grasp. After gaining some experience with it, I have valued the use and organization that classes can provide a program. This project was a very complicated one. It was very tough needing to think about all aspects of the program while writing it. There were plenty of times where I found myself stuck and didn't know how to precede. One thing I learned from this project is how to take a step back and look at the program as a whole. To forget the numerous files included and this of all of them as part of a whole. This helped remind me about how every part of the program is connected and how it all flows together. It reminded me to always take a step back and look at how the program needs to fit together in order for it to work, rather than getting stuck and focusing on only one part of the program that was not working. 
