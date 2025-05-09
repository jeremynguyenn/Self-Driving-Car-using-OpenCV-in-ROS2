# ROS2 Prius Self Driving Car  using AI/Deeplearning and Computer Vision

## Version Requirments
----
**Ubuntu-22.04 or Ubuntu-24.04 **  
**Gazebo**
**ROS2 Humble or ROS2 Jazzy**
- Python 3.6
- Opencv 4.2
- Tensorflow 2.14
----
## About this Repository
A Car in ROS2 will follow lane , Use AI to classify Sign Boards and perform Object tracking to act on the sign boards and set speed respectively
- ![alt text](https://github.com/jeremynguyenn/Self-Driving-Car-using-OpenCV-in-ROS2-/blob/main/Self-Driving-Car-AI/Images_videos/picdemo.png)

## Using this Repository
* Clone the repository in you Home folder 
```
git clone https://github.com/jeremynguyenn/Self-Driving-Car-using-OpenCV-in-ROS2-.git
```
* Get into the downloaded repository
 ```
 cd path/to/Self-Driving-Car-using-OpenCV-in-ROS2/
##e.g cd ~/Self-Driving-Car-using-OpenCV-in-ROS2/
  ```

* Bring all models into your **.gazebo/models**
 ```
 cp /models/* ~/.gazebo/models 
 ```
 or manually copy->paste them into ~/.gazebo/models/

* Perform Colcon Build
```
colcon build
```
* Source your Workspace in any terminal you open to Run files from this workspace ( Basics thing of ROS )
```
source /path/to/Self-Driving-Car-using-OpenCV-in-ROS2/setup.bash
```
* (Optional for Power USERs ) Add source to this workspace into bash file
 ```
  echo "source /opt/ros/noetic/setup.bash" >> ~/.bashrc
 ```
  **NOTE:** This upper command is going to add the source file path into your ~/.bashrc file ( Only perform it once and you know what you are doing).This will save your time when running things from the Workspace
----
## System Workflow
#### **Ros2 Package**
* World Models Creation
* Prius OSRF Gazebo Model Editing
* Nodes, Launch Files
* SDF through Gazebo
* Textures and Plugins in SDF

#### **Computer Vision** 
Perception Pipeline setup
Lane Detection with Computer Vision Techniques
Traffic Light Detection Using Haar Cascades
Sign and Traffic Light Tracking using Optical Flow
Rule-Based Control Algorithms
#### **DeepLearning**
Sign Classification using (custom-built) CNN

---
## Features
* **Prius Hybrid Car** 
  -  ![alt text](https://github.com/jeremynguyenn/Self-Driving-Car-using-OpenCV-in-ROS2/blob/main/Self-Driving-Car-AI/Images_videos/the_car.gif)
* **Lane Following** 
  -  ![alt text](https://github.com/jeremynguyenn/Self-Driving-Car-using-OpenCV-in-ROS2/blob/main/Self-Driving-Car-AI/Images_videos/lane_detection.gif)
* **Sign Board Detection**
  - ![alt text](https://github.com/jeremynguyenn/Self-Driving-Car-using-OpenCV-in-ROS2/blob/main/Self-Driving-Car-AI/Images_videos/traffic_signs_boards.gif)
* **Traffic Signal Recognition**
  - ![alt text](https://github.com/jeremynguyenn/Self-Driving-Car-using-OpenCV-in-ROS2/blob/main/Self-Driving-Car-AI/Images_videos/traffic_signal.gif)

* **j-Junction Navigation**
  - ![alt text](https://github.com/jeremynguyenn/Self-Driving-Car-using-OpenCV-in-ROS2/blob/main/Self-Driving-Car-AI/Images_videos/j_turning.gif)

* **The World** 
  -  ![alt text](https://github.com/jeremynguyenn/Self-Driving-Car-using-OpenCV-in-ROS2/blob/main/Self-Driving-Car-AI/Images_videos/world.gif)

* **Custom Models** 
  -  ![alt text](https://github.com/jeremynguyenn/Self-Driving-Car-using-OpenCV-in-ROS2/blob/main/Self-Driving-Car-AI/Images_videos/custom_models.gif)

* **Locolizatioin**
  -  ![alt text](https://github.com/jeremynguyenn/Self-Driving-Car-using-OpenCV-in-ROS2/blob/main/Self-Driving-Car-AI/Images_videos/Sat_Nav/1_localization.gif)

* **mapping**
  -  ![alt text](https://github.com/jeremynguyenn/Self-Driving-Car-using-OpenCV-in-ROS2/blob/main/Self-Driving-Car-AI/Images_videos/Sat_Nav/2_mapping.gif)

* **Path planning**
  -  ![alt text](https://github.com/jeremynguyenn/Self-Driving-Car-using-OpenCV-in-ROS2/blob/main/Self-Driving-Car-AI/Images_videos/Sat_Nav/3_pathplanning.gif)

* **Motion planning**
  -  ![alt text](https://github.com/jeremynguyenn/Self-Driving-Car-using-OpenCV-in-ROS2/blob/main/Self-Driving-Car-AI/Images_videos/Sat_Nav/4_motionplanning.gif)
----
## Video DEMO
- ![videodemo](https://github.com/jeremynguyenn/Self-Driving-Car-using-OpenCV-in-ROS2/blob/main/Self-Driving-Car-AI/Images_videos/videdemo.mp4)
