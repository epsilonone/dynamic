# Autonomous Navigation and Mapping with Dynamic Obstacles

This package creates and adds dynamic obstacles into the Gazebo simulation environment for autonomous navigation and mapping.

## Installation

### Step 1: Clone the Package

Clone the package into the `src` directory of your Catkin workspace:

```bash
cd ~/catkin_ws/src
git clone https://github.com/epsilonone/Autonomous-Navigation-and-Mapping.git

cd ~/catkin_ws
catkin build
# Or rebuild specific package
catkin build dynamic

roslaunch uuv_gazebo_worlds ocean_waves.launch



