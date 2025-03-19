# KIU_IntroToMl-AI

## TicTacToe

Here the logic is minimax: at each point if it is X's turn we ask which move gives us max score, and if it's O's turn we look for move that gives min score. By minimaxing all the way to the end (which is fine since tictactoe game always finishes in maximum of 9 moves since there's only 9 cells that are irreversibly filled), the computer will always choose the move that gives best score even if opponent makes best possible move

Logic for whose turn it is simple: if more X are present on board it is O's turn else it's X's turn