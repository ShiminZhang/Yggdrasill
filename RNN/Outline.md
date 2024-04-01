## Goal

This paper aims to give a through and concrete overview of Recurrent Neural Networks with precision.

It first introduces the origin and intuition behand RNN, which is to learn long range dependencies on sequencial tasks.

Then, it explains the early model of RNN and points out the problem with it. The early version of RNN has two problems, gradient descent and gradient explode. Some efforts are taken to alleviate those problem, including variations of activation functions.

The next part is about modern RNN. Naturally, modern RNN evolves to cope with gradient problems. This paper explains the structure and modifications of LSTM, BRNN and Neural Turing Machine.

The last part focuses on applications of RNN and the correspondence between different RNN structures and real world applications.