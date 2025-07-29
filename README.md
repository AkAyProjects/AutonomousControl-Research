# AutonomousControl-Research
A research project exploring deep learning and classical control methods for autonomous vehicle lateral motion planning. Based on my MASc thesis, this work compares model-based controllers with neural network approaches using MATLAB and SIMULINK

# 🚗 Deep Learning-Based Lateral Control for Autonomous Vehicles

This repository contains the core research, code, and results from my Master of Applied Science (MASc) thesis at Simon Fraser University. The project focuses on the development and comparative evaluation of model-based and AI-based lateral control methods for autonomous vehicle navigation.

---

## 📚 Overview

The goal of this research was to explore and benchmark traditional control algorithms (such as Stanley Controller and Pure Pursuit) against selected deep learning models for the task of **lateral path tracking** in self-driving vehicles.

---

## 🧠 Key Features

- 🚘 **Trajectory tracking** using classical control algorithms (Stanley, Pure Pursuit)  
- 🤖 **Deep learning models** trained on simulation data for steering prediction  
- 🧪 **Comparative analysis** of control accuracy, stability, and generalization  
- 📊 Visualization tools for loss curves, path deviation, and controller response  
- 🔁 ROS-compatible data pipeline for future extension  

---

## 🛠️ Tech Stack

- **Python, PyTorch, NumPy, Matplotlib**  
- **ROS (Robot Operating System)**  
- **CARLA Simulator / Custom simulation environment**  
- **Jupyter Notebooks for data exploration and training**  
- **TensorBoard for model diagnostics**

---

## 📂 Project Structure

MastersThesis-Control/
│
├── models/ # Deep learning architectures
├── controllers/ # Model-based control implementations
├── datasets/ # Training/testing data (simulated)
├── notebooks/ # Experiments & visualizations
├── results/ # Plots, metrics, and evaluation outputs
└── README.md


---

## 📄 Thesis Reference

If you're interested in a detailed write-up, methodology, and results, you can access the full thesis [here](https://events.sfu.ca/event/38253-mechatronics-masc-thesis-defence-akash-ayyagari).


---

## 🤝 Acknowledgments

Special thanks to my advisor, lab colleagues, and the Control Systems research group at SFU.
