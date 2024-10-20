# Autonomous Robot Navigation - Obstacle Avoidance System

## Overview
This project involves developing an algorithm for an autonomous robot to navigate through a rectangular warehouse, avoiding obstacles. The robot is equipped with sensors to detect obstacles and makes real-time decisions to navigate around them efficiently. 

The project showcases programming efficiency, algorithmic thinking, sensor integration knowledge, and simulation skills while incorporating creativity and innovation.

---

## 🚀 Project Objective
Design a **navigation system** for a robot operating in a structured warehouse environment. The robot must avoid **10 obstacles**, ensuring that no two obstacles are closer than 1 meter to each other. The robot's sensors can detect obstacles within a range of **0.2 meters**, and it must use this data to alter its path.

### Key Features:
- **Robot Specifications**:
  - Wheel Diameter: 10 cm
  - Distance Between Wheels: 30 cm
  - Linear Velocity: 1 m/s
  - Angular Velocity: 3 rad/s
- **Warehouse Setup**:
  - **Obstacles**: 10 obstacles are spread across the floor.
  - **Obstacle Avoidance**: Obstacles can be detected within a 0.2-meter range.
  
---

## 🧠 Algorithm Design
### Decision-Making Process
The core algorithm revolves around **sensor data** to detect obstacles and dynamically adjust the robot's movement:

1. **Obstacle Detection**: The robot uses its proximity sensors to continuously monitor for nearby obstacles.
2. **Path Calculation**: If an obstacle is detected within 0.2 meters, the robot calculates a new path to avoid it, ensuring minimal deviation from the desired trajectory.
3. **Steering**: The angular velocity of 3 rad/s allows the robot to make rapid directional adjustments to navigate around obstacles without significant delays.

---

## 📊 Evaluation Criteria

The robot's navigation system is assessed based on:

1. **Programming Efficiency**: Optimized code that ensures smooth and real-time navigation.
2. **Algorithmic Thinking**: The quality of the decision-making algorithm used for obstacle detection and path recalculation.
3. **Sensor Integration Knowledge**: Effective use of proximity sensors to detect and avoid obstacles.
4. **Simulation Skills**: Visualizing the robot's navigation through simulation tools.
5. **Creativity and Innovation**: Unique approaches and techniques to enhance the robot's navigation system.

---

## 🔧 Setup & Dependencies
### Installation
1. Clone the repository:  
   ```bash
   git clone https://github.com/abhinav26966/Autonomous-Robot.git

2. Install the required dependencies:
    ```bash
    pip install numpy
    pip install matplotlib

### Running the Project

1.  Execute the Jupyter notebook main.ipynb to observe the robot's decision-making process in action.
    
2.  Modify sensor settings or obstacle layout within the notebook for custom scenarios.
    

📈 Future Improvements
----------------------

*   **Enhanced Sensor Range**: Upgrade sensor detection to improve accuracy and response time.
    
*   **Dynamic Environments**: Enable the robot to navigate in dynamically changing environments with moving obstacles.
    
*   **Path Optimization**: Use machine learning to predict optimal paths and minimize travel time while avoiding obstacles.
    

📝 Assumptions & Limitations
----------------------------

*   The robot operates on a **flat and obstacle-rich surface** with obstacles placed at least 1 meter apart.
    
*   The algorithm assumes that the **environment is static** and the obstacles do not move during navigation.