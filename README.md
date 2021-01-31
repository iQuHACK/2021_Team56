# Welcome to Team56's Repo!
  
#### We are tyring to solve the Knapsack Problem
  
## Background
The knapsack problem is a classic optimization problem. We first tryied to convert it into a DQM problem. So instead of 0 or 1 as the status of the <img src="https://render.githubusercontent.com/render/math?math=x_i"> we use 0, 1, 2 and 3 (or more). The scenario is that we have a large container with several sections: A, B, C, etc, like different disks in a hard drive. To constrain those objects filled into the container, each section has its own weight limit while the sum of those is equal to the total weight limit of the container. However, for safety reasons, we can only fill the container with 90% of its total weight limit while each section could be fully filled. Then we have several initial options for objects, instead of 0 and 1, we have 0,1,2,.. and number represents which section you wanna put the object in and particularly 0 means the object will not be put inside the container. Other rules are the same with the knapsack problem.

## Goals
Using DQM we hope to solve this specific knapsack problem to get a solution showing which objects should be put into which specific sections in the container.

## Difficulty
The main difficulty we faced is that the algebra since the <img src="https://render.githubusercontent.com/render/math?math=x_i"> has values beyong 0 and 1. We tried to use a if condition to split <img src="https://render.githubusercontent.com/render/math?math=x_i"> into different variables (e.g. <img src="https://render.githubusercontent.com/render/math?math=\alpha, \beta, \gamma">) to represent whether the object is in a specific section or the container. But then it makes no sense to use a DQM method since variable can only take values of 0 or 1. We were trying to solve this but could not finish it in time so probably we're not in the correct direction.

## TO DO


### Participants: Guangpeng Xu, Akash Patel and Cecilia Josefa Pérez Muñoz

### Thank you!
