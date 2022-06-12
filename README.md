# Tetris

Tetris Assignment of Group 34 - BINGPOT

Our language is called 'CCLang'. Snippet of CClang is shown below. User can set the values as per his/her choice in the cclang_script.txt file.

```
BOARD: 15 15
CONTROLS: horizon = 1, set_speed = 2, GAME_MODE = 2
PIECE: @j, @z = "0110011011111111"
ACTION: changes()
FUNCTION: def changes(){ set_speed = 9 horizon = 0 return }

```

## To Run

Pre-requisites:

````
Python 3.6+
sly
````

## Run
Run the makefile that will compile all the files and execute the game with the following command:
NOTE: Your code should be in cclang_script.txt to compile successfully.
````
$ make
````


