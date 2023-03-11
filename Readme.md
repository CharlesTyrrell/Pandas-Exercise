# Intro
This is a basic demonstration of pandas and multiprocessing knowledge in python. Most documentation is in the python notebook itself

I used Jupyter Notebook for this project.

It is sectioned based on what I needed to accomplish in order to plot number of processes versus time of execution.
## Problem statement
* Create a large pandas data frame and fill it out with random numbers
* Split it into roughly equal chunks and using multiprocessing package in Python process chunks in parallel, one chunk per process  
* While processing each chunk, find medians for the rows being processed and then find maximums amongst those medians for the rows in each chunk; that maximum of medians is the result of processing for each chunk
* Then, when those results are collected from the individual processes, find the global maximum
* Implement time measurements and report timing results for a number of executions with different numbers of processors used
* Document code and try to provide as clean and nice of an implementation as possible; the code should be presentation ready and you should explain why you made specific choices and reason about them when we talk about it.

# To use
open in jupyter notebooks
run!