# Waypoint Tracking of Quadcopter in PX4-ROS

This repository provides a streamlined platform to perform waypoint tracking in quadcopter in ROS2, Gazebo and PX4.

### Software Stack

* ROS2 Humble
* Gazebo Harmonic
* PX4
* QGroundControl
* OffboardControl

### Trajectory of Quadrotor Navigation

![Alt text](images/sim_results/QGroundControl.png "QGroundControl")

![Alt text](images/sim_results/Gazebo.png "Gazebo-Quadcopter")

## **Installation Guide**

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

  ![Alt text](images/guide/reopen.png)
* Search for **"Dev Conatiners: Reopen in Container"** and select it to start building the container.

### **5. Run Tasks Inside the Container**

* Once inside the container, press ` Ctrl + Shift + P`  again.

  ![Alt text](images/guide/runtasks.png)t
* Search for  **"Run Tasks"** , then select and execute the  **following tasks** :

#### **Available Tasks**

* Below are the tasks avaliable

  ![Alt text](images/guide/tasks.png)

1. MicroXRCEAgent : Connection to ROS2 and PX4
2. PX4 SITL  : To start up PX4 with gazebo gui
3. QGroundControl : To launch QGroundControl
4. Sensor Combined Listener : To echo gyro readings and acceleration in all three axis
5. Offboard Control : To arm the vehicle and publish waypoint for quadcopter to track

## **Need Help? Raise an Issue!**

If you encounter any problems or have questions, feel free to **raise an issue.**
