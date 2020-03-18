## Team Members
Yuxiang Qian email: yuxiangq@uci.edu

Xiaolei Jiang email: xiaolej@uci.edu

Jeffrey Eric Su email: jesu@uci.edu

## GitHub Repo
```
https://github.com/yuxiangq777/175project.git
```

## Project Proposal

### Summary

In our project, there will be different mazes, and our project goal is that our AI successfully solve those mazes. Our project takes the blocks around the AI in each step as input, and the output is a sequence of action the AI should take.

### Evaluation Plan

  For the quantitative evaluation, the metrics will be the time/steps the AI takes to solve each maze, the number of times that AI successfully solve the maze and the number of times AI fails to solve the maze. The baseline should be that the AI can reach the terminal points with above 70% success rate when we do not consider the time limit. We should improve the metric over the baseline by about 10-20% success rate, and we can improve its performance by adding the time limit. In this project, we will evaluate the data of reward we set for the terminal points and obstacles in the maze, the blocks (maybe 3 * 3) around the AI which can affect its next move.
  
  For the sanity case that our project will definitely work on, we can have a maze with no obstacles like lava and give the AI unlimit time. To visualize the internals of the algorithm to verify it works, if we use Q-learning algorithm, we can print the value of Q function to see if it is been optimized. The "moonshot case" should be that we can pass any maze we write with above 90% success rate within limited time.

### Goals

Goal 1: Be able to solve simple mazes (five by twelve mazes which have set lava positions).

Milestone 1: Be able to solve simple mazes with above 70% success rate.

Milestone 2: Be able to solve simple mazes in under 20 seconds or within 50 actions.

Goal 2: Be able to solve medium level mazes. Medium mazes are five by twelve mazes with random lava obstacles.

Milestone 1: Be able to solve the medium maze with above 70% success rate.

Milestone 2: Be able to solve the medium mazes in under 16 seconds and within 100 actions.

Goal 3: Be able to solve hard level mazes. Hard mazes are twelve by twelve mazes with randomly generated lava and slime monsters.

Milestone 1: Be able to detect unsolvable mazes/solve with above 70% success rate.

### Video
https://www.youtube.com/watch?v=19KZK7K41z4

### Progress Report
<a href="https://yuxiangq777.github.io/175 progress report.pdf" target="_blank">Link</a>

### Presentation
<a href="https://yuxiangq777.github.io/175 presentation.pdf" target="_blank">Link</a>

