# Dual-Track EV Simulator 🏎️⚡

This project focuses on developing a simulation-based framework to **optimize the powertrain parameters of dual-track electric vehicles** under varying track and environmental conditions. By simulating lap times on racing circuits, the model helps identify EV configurations that **maximize performance and adaptability**.

---

## 🚀 Project Objectives
- Build an end-to-end simulation of EV dynamics
- Model vehicle dynamics, tire characteristics, and powertrain behavior
- Simulate lap times under different track and weather conditions
- Analyze how powertrain parameters affect performance (e.g., motor torque, battery capacity, traction)

---

## 📦 Key Modules

### 🔧 Vehicle Dynamics Modeling
- Dual-track model for turning, slip, and weight transfer
- Steering geometry and velocity profile computation

### 🛞 Tire Modeling
- Pacejka's Magic Formula or slip-force mapping
- Lateral & longitudinal force prediction

### ⚡ Powertrain Modeling
- Motor dynamics: torque-speed curves, efficiency maps
- Battery: discharge characteristics, thermal limits

---

## 📊 Results
- Simulated lap times across different tracks
- Power vs. weight tradeoffs
- Tire slip vs. acceleration plots

(You can include sample graphs or animations here)

---

## 🛠️ Tech Stack
- Python
- NumPy, Matplotlib, SciPy
- Jupyter for analysis
- (Optionally: ROS, Simulink, or Unity for future integration)

---

## 📁 Folder Structure
- `/src`: Core models
- `/data`: Sample input tracks and motor specs
- `/results`: Lap time results and plots
- `/notebooks`: Jupyter analysis notebooks

---

## ✅ Future Work
- Add thermal model of battery/motor
- Integrate reinforcement learning for real-time control tuning
- ROS-based Gazebo simulation for real-time performance

---

## 📄 License
MIT License
