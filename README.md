🧠 Cliff Walking RL: SARSA & Q-Learning

📌 Overview

This project implements reinforcement learning algorithms to solve the classic Cliff Walking problem.
An agent learns to navigate a gridworld environment by maximizing rewards while avoiding the cliff.

⚙️ Algorithms Implemented

🔹 SARSA (On-Policy)
• Learns from current policy behavior
• More conservative learning
• Safer path (avoids cliff consistently)

🔹 Q-Learning (Off-Policy)
• Learns optimal policy independent of actions taken
• Faster convergence
• Risk-taking behavior near the cliff.

✨ Features
• ε-greedy exploration strategy
• Training loop with reward updates
• Episode-wise performance tracking
• Gridworld environment simulation
• Learned policy visualization

🎮 Demo

<img width="1607" height="619" alt="Cliff walking agent - Q-Learning" src="https://github.com/user-attachments/assets/09bcd199-ef72-476d-959d-39dcbbc4dc45" />
                                          Cliff Walking Agent : Q - Learning

<img width="1655" height="555" alt="Cliff Walking Agent - SARSA" src="https://github.com/user-attachments/assets/d17730f8-7241-4578-8310-e8cdc73cf727" />
                                            Cliff Walking Agent - SARSA

📊 Results & Insights

• SARSA learns a safer policy, avoiding the cliff
• Q-Learning finds the optimal shortest path but may fall during training
• Demonstrates the trade-off between exploration and exploitation
• Highlights differences between on-policy vs off-policy learning

👩‍💻 Author
Likitha D

⭐ Support
If you found this project useful, consider giving it a ⭐ on GitHub!


