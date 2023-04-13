This deep learning project focuses on implementing and testing various reinforcement learning algorithms, 
including Deep Q-learning (DQN), Policy Gradients (PG), and Actor-Critic (AC). The test environment has 
four states and five actions, with different rewards assigned to each state transition. 
The goal is to maximize the sum of rewards in a single trajectory.

The project explores reinforcement learning with a focus on DQN. It highlights the challenges of training 
with non-stationary targets and correlated experience samples. The project addresses these issues with target networks and replay memory. 
The agent uses an epsilon-greedy exploration strategy and linear schedules for the learning rate and exploration probability. 
The Q network is implemented as a convolutional neural network (CNN).

The project then moves on to policy gradient methods, which optimize the policy directly by taking the gradient of the objective function. 
Techniques such as reward-to-go, discount factors, and state-dependent baselines are employed to reduce the variance of the estimates. 
The policy gradient is tested on classic control problems such as Cartpole and Acrobot, and the agent achieves good results in both tasks.

The importance of this project lies in understanding and implementing key reinforcement learning algorithms and techniques, 
demonstrating their effectiveness in solving different control tasks, and highlighting the challenges and solutions associated 
with training deep learning models for reinforcement learning. 
