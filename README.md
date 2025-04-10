# EC4.402: Introduction to UAV Design - Assignment II (Spring 2025)

## **Objectives**

The purpose of this assignment is to apply fundamental principles of **quadrotor dynamics and control** to determine the necessary acceleration inputs and perform flight simulations in  **ROS** . The key objectives include:

### **Q1. Acceleration Input Calculation (Python-Based Plotting)**

- Compute the required acceleration inputs (axd, ayd, azd) for a quadrotor to navigate between the given waypoints using Python.

- Consider a mass of 2 kg and assume a yaw angle ψ = 0°.

- Utilize inner-loop attitude control, ensuring perfect tracking of the desired roll (φd) and pitch (θd).

- Generate Python-based plots for:

- Acceleration (ax, ay, az) vs. time

- Desired roll (φd), pitch (θd), and thrust (Td)

- Velocity and position evolution in all three axes

### **Q2. ROS-Based UAV Simulation (PX4, Gazebo, Harmonic, ROS2 Humble, QGroundControl)**

* Implement a **ROS2 Humble-based simulation** to demonstrate quadrotor waypoint navigation using:
  * **PX4 Autopilot** for flight control.
  * **Gazebo Harmonic** for high-fidelity UAV simulation.
  * **QGroundControl (QGC)** for mission planning and monitoring.
* Simulate the quadrotor's motion toward each waypoint while logging  **position, velocity, and acceleration** .
* Generate **Python-based plots** to visualize flight dynamics, ensuring consistency with **Q.1 results**

### 3D Trajectory Plot of Quadrotor Navigation

This plot represents the **quadrotor's movement in 3D space**as it navigates through predefined waypoints. The simulation is based on the  **North-East-Down (NED) coordinate system** , illustrating changes in position over time.**

![3D Trajectory Plot](results_ROS_test/ROS_3D_Trajectory_Mission_A.png)

**Installation Guide**

### **1. Clone the Repository**

First, clone the project using Git:

bash

```
git clone https://github.com/Srindot/assignment2_Introduction_To_UAV_Design.git
```

### **2. Setup Docker**

Ensure Docker is installed and configured on your device.

### **3. Open the Project in VS Code**

* Launch  **Visual Studio Code (VS Code)** .
* Open the cloned project folder.

### **4. Build the Container**

* Press `Ctrl + Shift + P` to open the  **Command Palette** .
* Search for **"Reopen locally in a Container"** and select it to start building the container.

### **5. Run Tasks Inside the Container**

* Once inside the container, press `Ctrl + Shift + P` again.
* Search for  **"Run Tasks"** , then select and execute the  **following tasks** :

#### **Available Tasks**

1. MicroXRCEAgent
2. PX4 SITL
3. QGroundControl
4. Sensor Combined Listener
5. Offboard Control
6. ROS Bag Recording for Gyro Reading
7. ROS Bag Recording for Local Vehicle Accelerations

## **Need Help? Raise an Issue!**

If you encounter any problems or have questions, feel free to **raise an issue**in this repository. We'll be happy to assist you! 🚀
