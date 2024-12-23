<h1 align="center">Concurrent Design of UAVs for Real-Time Object Tracking</h1>

### 🚀 Project Overview
- **Challenge**: Achieving precise and efficient object tracking in dynamic environments.
- **Solution**: Combining YOLOv2 for rapid object detection with MOSSE for lightweight and adaptive tracking.
- **Focus**: Optimizing hardware and software co-design for real-time UAV performance.

---

### 🛠️ Methodologies

#### YOLOv2 Object Detection
- Provides rapid, frame-level object localization.
- Trained on a custom dataset of 2700 images.

#### MOSSE Tracking Algorithm
- A frequency-domain tracker that continuously adapts to dynamic environments.
- Lightweight and computationally efficient.

#### Optimization Framework
- Aligns hardware metrics (e.g., resolution, FPS) with software performance.
- Ensures energy-efficient operations without compromising tracking accuracy.

---

### 📊 Simulation and Results
- **Simulation Tools**: MATLAB and Unreal Engine.
- **Depth Cameras**: Used for precise distance estimation, avoiding costly LiDAR alternatives.
- **Performance**: Achieved a minimum Root Mean Squared Error (RMSE) of 0.35 in tracking accuracy.

---

### 🌟 Applications
This project has diverse applications, including:
- 🛟 Search-and-rescue missions
- 🐾 Wildlife monitoring
- 🎥 Live-event broadcasting
- 🔒 Security and surveillance

---

### 👨‍💻 Contributors
- **Aditya Bhatt**: Optimization and algorithm development.
- **Jagadeswara P K V Pothuri**: Simulation and practical implementation.

---

### 📜 License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

### 📚 References
1. Kumar, B. V., et al., "Minimum-variance synthetic discriminant functions," JOSA A, 1986.
2. Bolme, D. S., et al., "Visual object tracking using adaptive correlation filters," CVPR, 2010.
3. Jiang, P., et al., "A Review of YOLO algorithm developments," Procedia Computer Science, 2022.
