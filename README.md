# Gym Cartpole
CartPole is a structure where a pole is attached to the cart and the cart is free to slide across a frictionless surface. By sliding the cart left or right, the CartPole is balanced.

This repo aims to create a Q-Learning agent which:
- Uses the openAI gym environment “CartPole-v1”.
- Uses an 𝜖-greedy policy for exploration with 𝜖 = 0.05.
- Uses a learning rate of 𝛼 = 0.1.
- Uses a discount factor 𝛾 = 0.9.
- Has a maximum of 500 training episodes

Static_Epsilon_CartPole_5000_Episodes.ipynb implements the same code but for 5000 episodes rather than just 500.

Adaptive_Epsilon_CartPole.ipynb implements the same Q-Learning agent but with an adaptive 𝜖 and 𝛼.
