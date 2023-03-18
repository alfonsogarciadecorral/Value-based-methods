## Project 1

### Project Details
The aim of this project is teaching an agent to collect as many yellow bananas as possible.
The agent can move in 4 directions and reward will be +1 per yellow banana and blue per blue banana.

- Number of agents: 1
- Number of actions: 4
- States have length: 37 (velocity and ray-based perception)

The environment is considered solved once the average score is above 13 over 100 episodes. 

### Getting started
I had a huge amount of issues downloading the unityagents + torch dependencies. Therefore, I've being working on the workspace provided. 
The notebook Navigation.ipynb will contain all the code needed for the exercise.

I followed the same approach that in the dqn exercise. Just had to do minor changes for to adapt to the new problem.
The hyperparams fulfilled the requirements. So I decided to save GPU time for the time being and come back and play later once I've succesfully done the other two tasks.



### Instructions

The Navigation.ipynb file should run on the Workspace provided on the udacity platform.

Run the whole notebook. 
- Create the Model class
- Create the Agent class
- Create the Algorithm -- run it