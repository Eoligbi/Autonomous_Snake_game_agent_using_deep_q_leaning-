Autonomous Snake Game Agent Using Deep Q-Learning

This project implements an AI agent capable of autonomously playing the classic Snake game using Deep Q-Learning (DQN), a reinforcement learning technique. The agent is trained to maximize its score by consuming food and avoiding collisions with itself or the game boundaries, balancing exploration and exploitation to learn optimal strategies.

Features  
- Environment: Custom Snake game environment created using Pygame.  
- AI Model: Neural network with two hidden layers, designed to approximate Q-values for decision-making.  
Key Mechanisms  
  - Experience Replay: Stores and reuses game experiences for efficient training.  
  - Target Network: Stabilizes learning by periodically updating target Q-values.  
  - Epsilon-Greedy Policy: Balances exploration of new strategies with exploitation of learned ones.  
- Performance Metrics: Tracks scores, cumulative rewards, and convergence trends.  

Results
The trained agent consistently improves performance, achieving a best score of 150 and a mean score of 75 after 500 training episodes. 

Lessons Learned 
This project highlights the potential of reinforcement learning for sequential decision-making tasks, with opportunities for further optimization and scalability.

