# Rede-Neural-Atari
In this small project, I, using my knowledge of Python and A.I., created a small code capable of generating an A.I. that learned to play Atari, through Reinforcement Learning

To create this neural network, I used the Reinforcement Learning technique, using the Proximal Policy Optimization (PPO) algorithm. The main idea behind this algorithm is to avoid very sudden changes in the agent's policy. Because it doesn't use a replay-buffer (it doesn't record past experiences), it doesn't consume as much memory and the computational cost is reduced, while still being able to produce good results.

In the video I'm showing as an example, my AI is on the right, colored green. You can clearly see that it outperforms the CPU by leaps and bounds. It took around 4 hours to train it and over 3 million steps in total.

In this post, I've provided various points of interest about these techniques, as well as documentation and my own experiences, which I hope will inspire anyone who likes the subject.
