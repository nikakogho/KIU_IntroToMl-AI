# KIU_IntroToMl-AI

## TicTacToe

Here the logic is minimax: at each point if it is X's turn we ask which move gives us max score, and if it's O's turn we look for move that gives min score. By minimaxing all the way to the end (which is fine since tictactoe game always finishes in maximum of 9 moves since there's only 9 cells that are irreversibly filled), the computer will always choose the move that gives best score even if opponent makes best possible move

Logic for whose turn it is is simple: if more X are present on board it is O's turn else it's X's turn

## Degrees

Simple Dijkstra to check for neighboring people then their neighborings etc

## Knights

At first we give logic that each person is either knight or knave but not both
Then we say for each statement that either person saying it is a knight and statement is true, or person is knave and statement is false

## Shopping

Parsed csv to get evidence and labels, then trained and tested and got 38% sensitivity and 91% specificity

## Nim

AI plays against itself with Q learning, always chooses either best estimate value or random value if epsilon is enabled and random number on that turn is less than epsilon

Eventually AI is good enough I can't beat it

## Traffic

Used a convolutional neural network that
1. convolves the inputs through 32 filters
2. maxpools them on 2x2
3. convolves on 64 filters
4. again maxpools on 2x2
5. flattens the network
6. makes a dense connection to 128 nodes
7. gives output with softmax activation

## Parser

Came up with those non-terminals after some painful experimentation.
Made sure nonsensical sentences like "Armchair on the sat Holmes." fail, while all 10 samples pass

## Attention

``` python
tokenizer = AutoTokenizer.from_pretrained(MODEL)
inputs = tokenizer(text, return_tensors="tf")
```

These lines give input that has a list of numbers corresponding to tokens embedded in a numpy array, so we walk over it and find where we get the mask token id (103). Then we simply visualize for each layer's each head

## MicroGrad

Colab notebook [here](https://colab.research.google.com/drive/1-tzBU_h1tFsNMU2RLcOq61i17hsW73KO?usp=sharing)

## Trigram

Colab notebook [here](https://colab.research.google.com/drive/1a-6hTMm0nnKJGEY2tJAVt1ZZKZiQYvuf?usp=sharing)

## Multi-Layer Perceptron

Colab notebook [here](https://colab.research.google.com/drive/13TxU4KyKDUHh7LiE0AVZfRxdQwL83cK8)

## Backprop Ninja

Colab notebook [here](https://colab.research.google.com/drive/1eNBm4mhBWu220zd7atxkQmQtag0IIGoq?usp=sharing)
