# Gym Cartpole
CartPole is a structure where a pole is attached to the cart and the cart is free to slide across the frictionless surface. By sliding the cart left or right, the CartPole is balanced.

Create a Q-Learning agent. Show the reached optimal policy.
- Use the openAI gym environment “CartPole-v1”.
- Use an 𝜖-greedy policy for exploration with 𝜖 = 0.05.
- Use a learning rate of 𝛼 = 0.1.
- Use a discount factor 𝛾 = 0.9.
- A maximum of 500 training episodes is allowed. You should show your training
performance across episodes.

Static_Epsilon_CartPole_5000_Episodes.ipynb implements the same code but for 5000 episodes rather than just 500.

Adaptive Epsilon CartPole.ipynb implements the same Q-Learning agent but with an adaptive 𝜖 and 𝛼.