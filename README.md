# 🧠 Cliff Walking RL: SARSA & Q-Learning

## 📌 Overview
This project implements Reinforcement Learning algorithms to solve the classic **Cliff Walking** problem.

An agent learns to navigate a gridworld environment by maximizing rewards while avoiding the cliff, showcasing how different RL strategies behave under the same conditions.

---

## ⚙️ Algorithms Implemented

### 🔹 SARSA (On-Policy)
- Learns from the current policy behavior  
- More conservative learning approach  
- Finds a **safer path**, consistently avoiding the cliff  

### 🔹 Q-Learning (Off-Policy)
- Learns the optimal policy independent of actions taken  
- Faster convergence  
- Exhibits **risk-taking behavior** near the cliff  

---

## ✨ Features
- ε-greedy exploration strategy  
- Training loop with reward updates  
- Episode-wise performance tracking  
- Gridworld environment simulation  
- Learned policy visualization  

---

## 🎮 Demo

### Q-Learning Agent
![Cliff Walking Q-Learning](https://github.com/user-attachments/assets/09bcd199-ef72-476d-959d-39dcbbc4dc45)

### SARSA Agent
![Cliff Walking SARSA](https://github.com/user-attachments/assets/d17730f8-7241-4578-8310-e8cdc73cf727)

---

## 📊 Results & Insights
- SARSA learns a **safer policy**, avoiding the cliff  
- Q-Learning finds the **optimal shortest path**, but may fall during training  
- Demonstrates the **exploration vs exploitation trade-off**  
- Highlights differences between **on-policy vs off-policy learning**  

---

## 👩‍💻 Author
**Likitha D**

---

## ⭐ Support
If you found this project useful, consider giving it a ⭐ on GitHub!
