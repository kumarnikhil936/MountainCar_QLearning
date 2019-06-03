# reinforcement-learning-gym
Mountain Car is a classic reinforcement learning problem (solved here with Q-learning) where the objective is to create an algorithm which learns to climb a steep hill to reach the goal marked by a flag. 

The car’s engine is not powerful enough to drive up the hill without a head start so the car must drive up the left hill to obtain enough momentum to scale the steeper hill to the right and reach the goal.

Reinforcement learning technique called Q-Learning is used here to solve this problem. Q-Learning is an algorithm which attempts to learn a function or policy which takes an observation of the environment as input and returns an action as output. Q-Learning does this by determining which action is best in the current state as well as all future states.


References:

Reinforcement learning implemented with manual Q value update
https://www.youtube.com/watch?v=yMk_XtIEzH8&list=PLQVvvaa0QuDezJFIOU5wDdfy4e9vdnx-7&index=1

Reinforcement learning with a basic neural network in Pytorch
https://medium.com/@ts1829/solving-mountain-car-with-q-learning-b77bf71b1de2
