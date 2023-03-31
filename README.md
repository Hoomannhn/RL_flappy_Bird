# RL_flappy_Bird

This project explores the potential of Reinforcement Learning (RL) algorithms in the Text Flappy Bird (TFB) game environment. The TFB game is a text-based variation of the popular Flappy Bird game, providing a simple yet engaging environment for the study of RL techniques. The game environment has been implemented in the Text Flappy Bird Gym Gitlab, providing two versions: TextFlappyBird-screen-v0, which returns the complete screen render of the game, and TextFlappyBird-v0, which returns the distance of the player from the center of the closest upcoming pipe gap along the two axes (x, y).

The objective of the project is to implement and evaluate the performance of four Reinforcement Learning agents, including Q-Learning, SARSA, ExpectedSARSA, and Monte Carlo algorithms, within the TextFlappyBird-v0 environment. By comparing the performance of these agents in their ability to navigate the TFB environment, the project aims to uncover insights into the inner workings, strengths, and weaknesses of each algorithm.

The RL agents are implemented using a single class called Agent, which accepts the environment, the type of agent, and the parameters related to the learning process. The number of episodes is set to 5,000, and the discount rate, learning rate, and epsilon are defined as 0.95, 0.7, and 0.1, respectively.

The results show that Q-Learning and ExpectedSARSA agents generally perform better than Sarsa and MonteCarlo agents in terms of achieving the maximum score. However, the best agent may vary depending on the specific problem and environment.

This project demonstrates the potential of RL algorithms in solving problems in complex and dynamic environments. It also highlights the importance of choosing the appropriate RL algorithm for a specific problem, depending on the problem's characteristics and the available resources. By exploring and implementing different RL algorithms, we can improve the results of this project and apply RL techniques to a wider range of problems with varying complexities.
