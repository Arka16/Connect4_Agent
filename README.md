# Connect4_Agent


Description:

Connect 4 is a  two-player game played on a grid of six rows and seven columns. The objective is to be the first player to connect four of their colored discs( red or yellow) in a row, either vertically, horizontally, or diagonally.
I implement an AI agent to play Connect 4 against human players. The agent is able to predict optimal moves by using alpha-beta search, and the expectimax search algorithms.  By fine-tuning a heuristic function, the AI agent is able to achieve a 90% win rate against players.

Running the Game:

Fork/Clone this repository, cd into it. Then run python3 ConnectFour.py <arg> <arg>. where <arg>  can be any of the following:



ai: the player is the ai agent

human: You are the player

random: the player is an agent that generates random moves

Examples of commands:


-python3 ConnectFour.py human ai   means you are player 1 and the ai agent is player 2

-python3 ConnectFour.py ai random   means the ai agent is player 1 and the random agent is player 2

-python3 ConnectFour.py ai ai means the ai agent is both player 1 and 2 (the ai agent plays itself).


When playing as a human:

When it is your turn. Click on next move. The command line will prompt you to select a column to place your piece. Valid inputs are 0-6, 0 being the leftmost column and 6 being the rightmost column. You will not be able to place a piece on a column where all the spots are taken. 



