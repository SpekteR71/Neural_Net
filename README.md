# Neural_Net
Neural Network projects

This repository contains two projects, digit recognition and a chess AI

Digit recognition
A basic convolutional neural network to detect hand wriiten digits. Dataset used for this was the popular MNIST dataset.

Chess NN
This neural net predicts the evaluation of any given position of the board. This AI is best suited for beginners trying to understand chess tactics and strategies. The motive behind this project was the fact that even grand masters take a long time to understand and analyse moves made by powerful engines like AlphaZero of Stockfish. Therefore, we aimed at making a beginner friendly chess engine.

A new dataset was generated just for this purpose. The dataset contains a matrix representing the board position and stockfish evaluation for the same. Dataset size is apprximately 2.5gb and contains around 1.5 million different positions including opening, middlegame to endgame.

A simple minimax algorithm alonng with alpha beta pruning was implemented to enable decision making at each gamestate.

The neural network was trained and validated against stocckfish. The loss was expected but I noticed that the network played a few good moves occasionally. The network took approximately half an hour to play a game of about 25 moves at a depth of 4.

Further work can be done to make the network much faster and stronger.

I will include two trained models. Each trained using different activations and loss functions.
