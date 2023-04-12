# Snakey

A Snake game developed in C++. 

## Game Logic-Rules
This is a simple snake game. There's a snake head and tail and you get to control the snake head - up, down, left or right.
The tail follows. If you eat the fruit, the tail length increases. If the tail is hit by the wall of the map, the snake starts moving from the opposite wall. 
If the body or segment of the body or the tail hits the head, the snake dies and the game is over. 

Use the following keys to change the directions: - <br />
'a'- LEFT <br />
'd' - RIGHT <br />
'w' - UP <br />
's' - DOWN <br />
Press 'x' to quit the game <br />
Every fruit you hit, you gain +10 points. 

### How to play ?

Download the folder, and run the following commands in your terminal: -
```
g++ -o Snake snake.cpp 
```
```
./Snake
```
Enjoy playing :)
