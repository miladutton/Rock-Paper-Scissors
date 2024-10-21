# Rock Paper Scissors Lizard Spock Game

This is a version of the game Rock-Paper-Scissors with an exciting twist: **Rock-Paper-Scissors-Lizard-Spock**. In this version, two new weapons, Lizard and Spock, are added to make the gameplay more interesting and unpredictable. The user plays against the computer.

## How to Play

1.  You will be prompted to choose one of the five weapons:

    -   **Rock** 

    -   **Paper** 

    -   **Scissors** 

    -   **Lizard**

    -   **Spock** 

2.  The computer will randomly select one of the weapons as its choice.

3.  The outcome of the game is determined by the following rules:

    -   **Rock**: Crushes Lizard and breaks Scissors

    -   **Paper**: Disproves Spock and wraps Rock

    -   **Scissors**: Decapitates Lizard and cuts Paper

    -   **Lizard**: Poisons Spock and eats Paper

    -   **Spock**: Vaporizes Rock and smashes Scissors

## Game Logic

The game evaluates the result between the player's choice and the computer's choice:

-   If both the player and the computer select the same weapon, it results in a **tie**.

-   Based on the rules above, a winning or losing outcome is determined.

## Features

-   **Random Computer Choices**: The computer's choice is selected randomly using Python's `random` module.

-   **Win/Lose/Tie Conditions**: The game evaluates whether you win, lose, or tie based on your selected weapon.

-   **Interactive Prompts**: The game offers an intuitive prompt to select a weapon or ask for help.

-   **Help Function**: Type `help` during the game to see a list of rules and instructions.

## Game Flow

The game consists of several custom functions:

-   **consist**: Checks the player's input for validity.

-   **opponent**: Randomly selects a weapon for the computer.

-   **rock, paper, scissors, lizard, spock**: Define the winning conditions for each weapon.

-   **gameon**: Evaluates the game result (win, lose, tie).

-   **hooray**: Displays the result and celebrates the winner.

-   **myprompt**: Prompts the player to choose a weapon and runs the game.

-   **mythrill**: Adds suspense before revealing the choices.

-   **myhelp**: Provides game rules and instructions.
