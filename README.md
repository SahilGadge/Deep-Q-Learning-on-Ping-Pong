# Deep-Q-Learning-on-Ping-Pong
Deep Q Learning is the reinforcement learning algorithm which uses prior experience to take future actions. In this Project I'm using various Deep Q learning algorithm to play Atari games.


Q-learning is a model-free, value-based, off-policy learning algorithm.


> Model-free: The algorithm that estimates its optimal policy without the need for any transition or reward functions from the environment.


> Value-based: Q learning updates its value functions based on equations, (say Bellman equation) rather than estimating the value function with a greedy policy.


> Off-policy: The function learns from its own actions and doesn’t depend on the current policy.

Steps:

 Q model. The learning process will follow these steps:

1.   Initialize the Q-values table, Q(s, a).
1.   Observe the current state, s.
1.   Choose an action, a, for that state based on one of the action selection from policies like - (-soft, -greedy or softmax).
2.   Take the action, and observe the reward, r, as well as the new state, s'.
2.   Update the Q-value for the state using the observed reward and the maximum reward possible for the next state. The updating is done according to the forumla and parameters described above.
2.   Set the state to the new state, and repeat the process until a terminal state is reached.
