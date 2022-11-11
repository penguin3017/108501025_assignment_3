# Data Structure HW3: Shogi in C (linked list)
#### 電機4B 108501025 沈冠璋

## Please download libev at my HW2: https://github.com/penguin3017/108501025_assignment_2.git

The program can **create a new game of shogi** or **load a manual of shogi** 
How to play the game:
1. First, the system will ask you whether you would store the manual
   + press  **"n"** for no
   + press  **"s"** for yes, and the system will create a file called **"new_game.txt"**
2. System will show this turn is for player x or player y
3. System will ask you to enter the chess you want to move, please type the **column** of the chess
   + If you want to regret, you can enter the number "0" for recovering **one** step 
4. Enter the row of the chess you want to move, and the destination of the column、row **in order**
5. The system will show you the time you take in **second**
5. Repeating 1~4, you can enjoy the game !!

How to load a manual:
1. The system will ask you decide what to do next
   + press **f** for next step
   + press **b** for last step
2. If the manual is done, the system will remind you **The all record is finished!** and quit

## How to Compile & Run
```sh
# Compile
gcc -o bb main.c stk.c -lev

# Run (Playing a new game)
./bb –n –s new_game.txt

# Run (Loading a manual of shogi)
./bb –l new_game.txt
```
