[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-8d59dc4de5201274e310e4c54b9627a8934c3b88527886e3b421487c677d23eb.svg)](https://classroom.github.com/a/S8i0Ljb1)
# Challenge Problem 5

## Deadline: March 24, 2023 by midnight

Note: While high-level discussion is allowed and encouraged for the challenge problems, these problems should be completed and submitted individually.

### Description

Run through the guide at [RNN guide](https://www.tensorflow.org/guide/keras/rnn). Then, answer the following questions.

### Part 1: Keras

1.   Give 1-2 sentence description of keras.

The Keras recurrent neural network (RNN) API is a customizable and easy to use way you can model sequence data. Keras uses layers with different attributes to make different models such as a `Sequential` model of given data.

2.   Give a short explanation of the following:

- `Embedding` - Embedding layers involves mapping variables to vectors of data. 
-  `Dropout` - In RNNs dropout is like the noise that is dropped from the neural network in a means for improving results

### Part 2: Unidirectional vs Bidirectional

1.   Give 2-3 sentence explanation of how bidirectional RNNs are different from unidirectional RNNs.

One way bidirectional RNNs are different from unidirectional RNNs is that bidirectional RNNs look at the context around the word whereas unidirectional do not. Bidirectional models require additional training because it looks at information from in front of the current focus and behind. On the other hand, Unidirectional RNNs only take information from the past.


### Part 3: Add code

1.   Include the code from "Recurrent Neural Networks (RNN) with Keras" guide that you ran (must show output) as a Google Colab notebook in your challenge 5 repository.
