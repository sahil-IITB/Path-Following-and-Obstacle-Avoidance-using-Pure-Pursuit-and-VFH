# IIT Bombay Unofficial LaTeX Lab Report Template  

This repository contains a LaTeX lab report template for **EE615: Control and Computational Laboratory** at IIT Bombay.  
This report documents **Experiment No. 2: Path Following and Obstacle Avoidance using Pure Pursuit and VFH**.  

---

## 📌 Contents
- **Introduction** – Motivation and overview of Pure Pursuit and VFH algorithms.  
- **Aim** – Define navigation goals (waypoints with obstacle avoidance).  
- **Objective** – Implement Pure Pursuit in Simulink, VFH in MATLAB/Simulink, integrate both, and evaluate performance.  
- **Experimental Setup** – MATLAB/Simulink environment, differential drive robot, range sensors.  
- **Block Diagram** – System workflow for navigation.  
- **Procedure**  
  - Pure Pursuit: Look-ahead geometry, curvature calculation, steering control.  
  - VFH Algorithm: Histogram grid, polar histogram, smoothing, valley selection, steering angle computation.  
- **Results** – Tuning parameters for Pure Pursuit and VFH; simulations with various waypoints.  
- **Challenges Faced** – Overshooting, oscillations, parameter tuning, local minima, computational load.  
- **Limitations** – Sensitivity to sensor noise, difficulty in narrow passages, lack of long-term planning.  

---

## ⚙️ Features
- Implemented **Pure Pursuit Algorithm** for path following.  
- Developed **Vector Field Histogram (VFH)** for obstacle avoidance (without built-in functions).  
- Integrated both for **robust local navigation**.  
- Demonstrates simulations with **static and dynamic obstacles**.  
- Suitable as a reference template for **robotics experiments** in MATLAB/Simulink.  

---

## 🚀 How to Use
1. Clone or download this repository.  
2. Open the `.tex` file in your LaTeX editor (Overleaf, TeXStudio, or VS Code).  
3. Compile using `pdflatex`.  
4. Replace experiment details with your own work.  

---

## 📚 Example Experiment  
**Path Following and Obstacle Avoidance using Pure Pursuit and VFH**  
- **Pure Pursuit:** Implemented curvature-based path tracking.  
- **VFH:** Designed polar histogram-based obstacle avoidance.  
- **Integration:** Achieved smooth motion while avoiding static and dynamic obstacles.  
- **Performance Metrics:** Path accuracy, smoothness, and obstacle avoidance success.  

---

## 👥 Contributors
- Sahil Patil (Roll No. 24M1087)  
- Shivangi Sharma (Roll No. 24M0027)  

---

## 📄 License
This project is for academic and learning purposes.  
You are free to use and modify the template.  

---
