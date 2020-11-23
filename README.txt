# CS 7641 Assignment 4: Markov Decision Processes
## Author
Name: Tianyu Yang<br>
GTid: 903645962<br>
Date: 2020/11/22<br>

## Introduction
This project is to generate two MDP problems(actually three), one for frozen lake and one for taxi. I use value iteration, policy iteration and reinforcement learning algorithm(Q learning) to solve this problem. I compare with the count of iterations, running time and scores for each of the problems and algorithms.

This project link on Github: https://github.com/simonyang0701/CS7641-Markov-Decision-Processes.git<br>


## Getting Started & Prerequisites
To test the code, you need to make sure that your python 3.6 is in recent update and the following packages have already been install:
gym numpy collections functools time

## Running the Classifiers
Recommendation Option: Work with the iPython notebook (.ipnyb) using Jupyter or a similar environment. Use "Run ALL" in Cell to run the code. Before running the code, make sure that you have already change the path into your current working directory
Another Option: Run the python script (.py) after changing the directory into where you saved the two datasets
Other Option (view only): Feel free to open up the (.html) file to see the output of program

The Optimization Algorithms are divided into three parts:
1. Importing useful packages
2. Functions for value iteration, policy iteration and Q learning algorithm.
3. Count the iteration, time and scores for each of algorithm on each problem