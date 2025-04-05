# 🚦 Smart Traffic Light Control using Q-Learning (Jupyter Notebook)

This project demonstrates a simplified simulation of a smart traffic light system powered by **Reinforcement Learning (Q-Learning)**. The goal is to reduce congestion at a single intersection by making intelligent decisions about when to switch traffic phases based on real-time queue data and incidents.

---

## 📚 Project Overview

The system simulates:
- **TrafficLightAgent**: Learns to switch signals using Q-learning to minimize queue congestion.
- **VehicleAgent**: Represents vehicles moving north-south (NS) or east-west (EW), including emergency vehicles.
- **DroneAgent**: Randomly detects incidents like accidents that block routes temporarily.
- **TollAgent**: Adjusts toll pricing dynamically based on congestion.

The simulation runs in discrete steps, with the environment updating states, collecting rewards, and visualizing system performance.

---

## 🧠 Features

- 🔁 **Q-Learning Agent** that learns optimal switching strategy
- 🚓 **Emergency Vehicle Handling** to ensure priority
- 🚁 **Incident Detection** using Drone agent
- 💸 **Dynamic Toll Pricing** based on traffic load
- 📊 **Visualization** of queue lengths, tolls, rewards, and cleared vehicles
- 🤖 Optional: Deep Q-Network (DQN) agent for performance comparison

---

---

## ⚙️ Setup Instructions

### 1. Install Dependencies

You can install required packages using pip:

```bash
pip install -r requirements.txt

```
requirement.txt

numpy
matplotlib
torch
notebook


## How to Run the Simulation

Open smart_traffic_light.ipynb.

Run all cells (Kernel > Restart & Run All).

Observe printed logs and visual plots for performance evaluation.


## Visual Outputs
At the end of the simulation, the notebook produces:

🚦 Queue Length Over Time (NS, EW, Total)

💸 Toll Pricing Over Time

📈 Cumulative Reward Plot

🚗 Vehicles Cleared Over Time

🧠 Top Q-values Learned from training

## 🧪 How to Test
You can test different configurations by modifying parameters:

In the TrafficEnvironment:

num_vehicles: Total number of vehicles

emergency_vehicle_probability: Chance of emergency vehicles

In the TrafficLightAgent:

alpha: Learning rate

gamma: Discount factor

epsilon: Exploration rate

After changes, re-run the cells to see updated behaviors and performance metrics.

## 🚀 Future Enhancements
🤖 Implement and compare Deep Q-Network (DQN) performance

🏙️ Simulate a grid of multiple intersections

🛰️ Use real-time traffic data inputs

📱 Develop a UI using Streamlit or Voila

🧪 Train over multiple episodes to improve learning stability

![image](https://github.com/user-attachments/assets/379afc96-0d3a-485d-9ef3-1e6fccd1c288)

![image](https://github.com/user-attachments/assets/1a47fc8e-865f-4b1f-90c7-c2dcc5c1dadd)


