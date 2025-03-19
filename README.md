# KIU_IntroToMl-AI

## TicTacToe

Here the logic is minimax: at each point if it is X's turn we ask which move gives us max score, and if it's O's turn we look for move that gives min score. By minimaxing all the way to the end (which is fine since tictactoe game always finishes in maximum of 9 moves since there's only 9 cells that are irreversibly filled), the computer will always choose the move that gives best score even if opponent makes best possible move

Logic for whose turn it is is simple: if more X are present on board it is O's turn else it's X's turn

## Degrees

Simple Dijkstra to check for neighboring people then their neighborings etc

## Knights

At first we give logic that each person is either knight or knave but not both
Then we say for each statement that either person saying it is a knight and statement is true, or person is knave and statement is false