NAME - Prisha Patel
NSID - sxc436
Course - CMPT 145 (summer/spring)


# ConwaysGameoflife

#Description 

The goal of the project is to draw the game named Conway's Game of LIfe. The gaames evolution is determined by its initial state and requires no input. One interacts the game by setting up the initial inout and observing how the input evolves.

##Design, decisions and idea

1. Grid Representations - 
Decision - I will represent the game grid as two dimensional array, where each cell can even be alive or dead. 
Reason - This representation gives me an easy access to maniuplate the cells of array during the games evolution. Chosing this representation is because it aligns well with the grid like representation of the game.
Goals - To create the software correct and efficient, adaptable and reuseable.

2.Function Structure - 
Decision -  I will design the program to have a main function named 'next_generation', which will serve as the entry point for execution. Additionally, I will create separate functions for updating a grid into the separate function 'count_live_neighbours'
Reason - This modular structure enhances code readability, reusability, and testability.
Goals - To create the software correct and efficient, adaptable and reuseable.

## Design Goals

1. Correct and Efficient Software
To ensure correctness, I will use test-driven development (TDD) principles. I will write unit tests to cover different aspects of the game's behavior, such as cell state transitions and boundary conditions. By writing tests first, I can verify the correctness of the implementation and catch any issues early.

For efficiency, I will aim to optimize the update process. Instead of traversing the entire grid for each cell, I will maintain a set of live cells and only update the state of those cells and their neighbors. This approach avoids unnecessary computations for dead cells.

2. Robust Software
To make the software robust, I will implement error handling mechanisms. For example, I will check for valid input file formats and handle any potential exceptions or errors that may occur during file operations. Robust error handling will prevent the program from crashing and provide informative error messages to users.

3. Adaptable Software
To ensure adaptability, I will design the code to be modular and loosely coupled. This will allow for easy modification or extension of functionality in the future. For instance, if the grid size needs to be expanded beyond the initial specifications, the code can be easily modified to accommodate larger grids without significant changes to the core logic.

4. Reusable Software
I will aim to write clean, readable, and well-documented code, following best practices and adhering to coding standards. This will make the software more reusable, both within the current project and potentially in other projects. Reusable code components can be extracted and organized into separate modules or libraries, making them easily accessible and adaptable for future use.

##How do I know the program will work correctly?
I would try do unit testing to check the correctness of each individual function.

##What Situations may break my code?
there are several situations which may result breaking up my code the most important one is the invalid grid size and incorrect format of input.

##Are there ways to make the program more efficient?
I am unsure of that but therer could be a way where the program could be made more efficiently.

##Have I made choices that reduce future adaptability?
The design of the program would redue the future adaptability as due to the choices such as grid representation which cannot take irregular shapes grids, the boundary condition where cell outside the grid are considered dead. This are the design choices which makes the code less future adaptible.

##Which parts of this program might be useful in another project?
Both the functions used in the program 'next_generation' and 'count_live_neigbhors' can be used in the another project containing the grid fuctions and manipulations same as this game.

##What design decisions/ choices/ assumptions you made.
the decision, choices and assumptions done for the design are just the basic fundamentals as follows-
1.the size of the grid cannot be changed at the middle of the program once it starts running.
2. the grid representation alive cell is denoted by 1 and the dead cell is denoted by 0.

##What ways you allowed for your to be extended.
to get the extensions we can change the grid size to flexible.

##What design ideas you changed or altered from your original design plan and
why.
this code was the basic implementation of two fuctions as decided to be designed so no changes everything ran smoothly.

##What risks, bugs, or unfinished aspects exist, and where the issue may lie, or the
way to resolve them, if there was more time.
the expects i find is unfinished is the code should have been more flexible in terms of its boundary conditions.

##What aspects of the program have been completed.
based on the information given I have tried to count the number of live neigbhors for each cell.

##Ways you might consider extending the program if there was more time.
for extension I would have try to implement the logic of using irregular shape grids.
