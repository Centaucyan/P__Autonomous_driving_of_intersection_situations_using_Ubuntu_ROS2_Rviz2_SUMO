# P__Autonomous_driving_of_intersection_situations_using_Ubuntu_ROS2_Rviz2_SUMO

## 1. Environment
* **OS:** Ubuntu 22.04
* **Language:** C++
* **Middle ware:** ROS 2 Humble
* **Simulator:** SUMO (Simulation of Urban MObility)
* **Visualization Tool:** RViz 2

---

## 2. Install
### 2.1. SUMO
* **Reference site:** https://sumo.dlr.de/docs/Installing/index.html
* sudo add-apt-repository ppa:sumo/stable
* sudo apt update
* sudo apt install sumo sumo-tools sumo-doc
* echo "export SUMO_HOME=/usr/share/sumo" >> ~/.bashrc
* source ~/.bashrc