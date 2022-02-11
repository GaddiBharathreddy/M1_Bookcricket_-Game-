# Requirements
 ## Introduction
The project  **Book Cricket Game** and developed using C language. Book Cricket is an indoor game which can be played by two players with a book.This game is made for two players. The two players will have to decide who is going to guess the toss. After winning the toss, the player has to choose whether he has to bat/bowl first. The player who idecided to bat first, need to hold the book. He has to randomly open the pages of the book and look for the last digit of that page number which is nothing but the runs scored in that particular ball. If the last digit is 7/8/9, then it will be considered as a dot ball. The  score obtained will be added to the batsman's score everytime. The batsman is out if the number is 0. Then, the second player starts batting  in the same process.
### Advantages
 - Improved engagement with the players
 - Easy and faster access 
 - best, longer-lasting customer relationships
 - Increas productivity with relaxation
 - No need of  memory for storage 
 - Random values generated makes our game more interesting.
 
 ### Disadvantages
 - GUI is needed
 - two players can play this game
 - Leaderboard not implemented
 - previous game statistics not stored.
 
## Cost and Features
 - Complexity 
 - Random Functional values generation
 - sum of the players score individually
 
Book Cricket have features like:
 -  Reading the names of the both players. 
 - Asking the player to select Head/Tail during toss.
 - player who won the toss chooses to bat/bowl.
 -  Counting the score of each individual.
 - Announcing the winner of the game.
 - Displaying the name of the winner.
## SWOT Analysis

# 4 W's and 1 H
## Who
Every person who is having mobile need games now a days.
## What
A book cricket game where two players can play with each other almost like real cricket.
## When
Due to the pandemic sitations, no one can go out and play cricket, so they can play this book cricket .
## Where
It can be played by everyone and everywhere irrespective of their age. 
## How
This application was developed in C language to avoid the complexity and to keep it simple. 
# Detail Requirements
## High Level Requirements
| ID | Description | Status |
|--|--|--|
| HR01 |Main Menu  | Implemented |
| HR02 | Can be played by 2 players | Implemented |
| HR03 | Toss |  Implemented |
| HR04 | Batting/Bowling |  Implemented |
| HR05 | Graphical User Interface | Future |
## Low Level Requirements 
| ID | Description | HR ID | Status |
|--|--|--|--|
| LR01 |Main menu should consist 4 options asking for 1.Limited Overs 2.Play Until Out 3.Instructions For the Game 4.Quit  | HR01| Implemented |
| LR02 | Reading the names of the two players and asking for the selection of head/tail while tossing the coin. | HR02| Implemented |
 LR03 | Implementing a function which takes the users according to the toss for the next steps which are batting/bowling. | HR03| Implemented |
| LR04 | If user searches for an invalid key "Invalid Input" message should be displayed | HR03| Implemented |
| LR05 |Implementing a fnction named batting which returns the total sum of the score of the two players. | HR04| Implemented |
| LR06 |A clean graphical user interface with all required buttons for ease of use  | HR05| Future |