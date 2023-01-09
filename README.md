# XOR Neural Network Simulation

## Introduction

XOR cauculation using neural network and dynamic memory allocation in C language.

## Description

This project shows that a XOR neural network simulation using the back-propagation learning algorithm by using dynamic memory allocation. In the input layer, there are two input layer neurons, which is 1 and 0. There are 4 ideal situations, which are 0^0=0, 0^1=1, 1^0=1, 1^1=0. There are three hidden layers, which has 3, 4, 3 hidden layer neurons. Lastly, there is one output layer neuron, which is the simulation result. At each epoch, I also add loss function related to the ideal case and the simulation result. At the final representation, you can see the ideal cases and the simulation results.

## Compile

```
gcc main.c -o main.out
```

## Operation

```
./main.out
```

## Reference

1. [https://github.com/mayurbhole/Neural-Network-framework-using-Backpropogation-in-C]
2. [https://github.com/cgera13/XOR-Neural-Network]
3. [https://www.geeksforgeeks.org/implementation-of-artificial-neural-network-for-xor-logic-gate-with-2-bit-binary-input/amp/]
4. [https://towardsdatascience.com/simple-neural-network-implementation-in-c-663f51447547]
5. [https://medium.com/analytics-vidhya/building-neural-network-framework-in-c-using-backpropagation-8ad589a0752d]
6. [http://neuralnetworksanddeeplearning.com/chap2.html]