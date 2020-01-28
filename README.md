## Team Members
Yuxiang Qian email: yuxiangq@uci.edu

Xiaolei Jiang email: xiaolej@uci.edu

Jeffrey Eric Su email: jesu@uci.edu



## Project Proposal

### Summary

In our project, there will be different mazes, and our project goal is to reach the terminal points of them and get out of those mazes. Our project takes the blocks around the AI in each step as input, and the output is a sequence of action the AI should take.

### Evaluation Plan

  For the quantitative evaluation, the metrics will be the time/steps the AI takes to get out for each maze, the number of times that AI successfully get out of the maze and the number of times AI fails to get out of the maze. The baseline should be that the AI can reach the terminal points with above 70% success rate when we do not consider the time limit. We should improve the metric over the baseline by about 10-20% success rate, and we can improve its performance by adding the time limit. In this project, we will evaluate the data of reward we set for the terminal points and obstacles in the maze, the blocks (maybe 3 * 3) around the AI which can affect its next move.
  For the sanity case that our project will definitely work on, we can have a maze with no obstacles like lava and give the AI unlimit time. To visualize the internals of the algorithm to verify it works, if we use Q-learning algorithm, we can print the value of Q function to see if it is been optimized. The "moonshot case" should be that we can pass any maze we write with above 90% success rate within limited time.

### Goals

```content
Goal 1: Find a Diamond Block within 100 minecraft days.
Milestone 1: Craft a stone pickaxe (would need to first obtain wood -> wood pickaxe -> stone)
Milesteon 2: Begin searching/mining for diamonds.
Goal 2: Find a Diamond Block and mine it to obtain an diamond in 50 minecraft days.
Milestone 1: Locate a diamond within 50 minecraft days
Milestone 2: Obtain iron and craft iron pick
Goal 3: Find enough diamonds to make a diamond chestplate (8 diamonds needed) in 25 minecraft days.
Milestone 1: Find diamonds in 25 minecraft days.
```

### Appointment date/time

```content
Our appointment will be on 1/31 Friday 10:30 am at DBH 4064
```
