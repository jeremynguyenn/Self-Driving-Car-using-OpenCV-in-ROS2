# ROS2 Prius Self Driving Car  using AI/Deeplearning and Computer Vision

## Version
----
**Ubuntu-22.04 or Ubuntu-24.04 **  
**Gazebo**
**ROS2 Humble or ROS2 Jazzy**
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
* If the repository is not working for you. Watch the free preview video on our course page 
 in **Section # 6 : How to use Code** where full explaination is given on setting up this repository.
  * **[[Link not added Yet !]]()**
