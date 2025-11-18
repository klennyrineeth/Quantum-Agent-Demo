# 🌌 **Quantum Agent – Reinforcement Learning Maze Navigation**

Quantum Agent is an autonomous reinforcement learning (RL) system designed to navigate a maze-like grid environment using intelligent decision-making.
Instead of relying on predefined paths or manual logic, the agent learns through exploration, rewards, and continuous improvement.

This project demonstrates how RL can be used to build self-learning agents capable of navigating complex environments — similar to real-world robots or intelligent systems.

---

## 🚀 **Project Summary**

Quantum Agent is trained using the PPO (Proximal Policy Optimization) algorithm to explore a maze, avoid walls, and reach a target goal.
The agent begins with random movement but gradually learns efficient navigation strategies through trial and error.

This repository contains:

* 🎥 A video demonstration of the agent
* 🧭 A moving HTML simulation of the maze
* 🧩 Maze images & agent movement visualizations
* 📈 Training curves showing improvement
* 💡 A clean, simple interactive webpage (index.html)

---

## 🎯 **Problem Statement**

Manually building navigation logic for maze environments becomes difficult as complexity increases.
Traditional algorithms require rules, predefined paths, and extensive tuning, making them hard to scale.

Reinforcement Learning solves this by allowing an agent to learn:

* how to move
* how to avoid obstacles
* how to reach goals
* how to adapt to new layouts

However, RL requires proper environment design, reward shaping, and visualization.

Quantum Agent aims to **simplify and showcase** this entire process.

---

## 💡 **Solution Statement**

Quantum Agent uses a PPO-based RL strategy to autonomously learn maze navigation.
The agent interacts with the environment, receives rewards, and updates its policy until it can reach the goal efficiently.

The solution includes:

* A grid-world maze
* Automatic path-learning
* Reinforcement-based movement
* Agent demonstration through video
* HTML simulation showing agent behavior visually
* Training performance metrics

This creates a fully understandable and interactive RL project experience.

---

## 🧱 **Project Architecture**

### **1. Environment**

A grid-based maze with:

* walls
* open spaces
* agent start
* goal node

### **2. RL Algorithm – PPO**

Handles:

* policy updates
* decision-making
* reward optimization
* exploration vs exploitation

### **3. Agent**

Learns:

* step-by-step navigation
* optimal pathfinding
* how to avoid dead-ends

### **4. Visual Demo**

* HTML simulation
* Video demonstration
* Images and curves

---

## 🖥️ **Live Demo (HTML Maze Movement)**

Open the hosted HTML version (if GitHub Pages enabled):

👉 *Will appear here once GitHub Pages is activated*

---

## 🎥 **Demo Video**

YouTube link (add your link here):
👉 *[https://youtube.com/](https://youtu.be/z6N-2wGqvt8)...*

Or download the video from `/media/` folder.

---

## 🖼️ **Project Media**

The `/media` folder contains:

* Maze image
* Agent movement visualization
* Training curve
* Demo video (MP4)

These support the project explanation for Kaggle judges.

---

## 📁 **Repository Structure**

```
Quantum-Agent/
│
├── index.html
├── README.md
│
├── media/
│   ├── quantum_agent_demo.mp4
│   ├── maze_image.png
│   ├── agent_path.png
│   ├── training_curve.png
│
└── (optional) src/
    ├── train_agent.py
    ├── evaluate_agent.py
```

---

## 🏁 **How It Works**

1. The agent starts exploring the maze
2. PPO updates the policy based on rewards
3. The agent learns to navigate efficiently
4. A video + HTML simulation visualize the movement

---

## 🔮 Future Improvements

* Multi-agent cooperation
* Dynamic moving obstacles
* Random maze generation
* Curriculum learning
* Larger grid environments

---

## 💛 **Created By**

**Rineeth Chandavarapu (Quantum Agent Developer)**
