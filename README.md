# A Framework for Generating Synthetic Expert Demonstrations in Digital Twin-based Robot Learning

This repository is part of the paper, [A Framework for Generating Synthetic Expert Demonstrations in Digital Twin-based Robot Learning](https://ieeexplore.ieee.org/document/11205394), presented at the 2025 IEEE 23rd Jubilee International Symposium on Intelligent Systems and Informatics (SISY).

In order for our results to be repeatable, this repository serves as a collection for our other repositories, used in the paper.



## Repositories
-  [onrobot-ros2](https://github.com/ABC-iRobotics/onrobot-ros2/tree/c6e390313e831a2e54a0ad5894b2911cc360a16a) – Onrobot RG6  control library, used for controlling the simulated gripper.
-  [tmr-ros2](https://github.com/TechmanRobotInc/tmr_ros2/tree/humble) – Techman Robot ROS 2 driver, used to connect the simulated robot with real, or externally simulated robot. Optional, ROS 2 spawners and topic based contorl can be used.
-  [tm5-900_rg6_moveit_config](https://github.com/ABC-iRobotics/tm5-900_rg6_moveit_config/tree/6b10b7d3bc07619211080f630722994fbe4d15f4) – TM5-900 MoveIt2 configuration with the OnRobot RG6 gripper. This repository also contains the USD for the robot, and the Isaac Sim scene used in the paper.
-  [isaac_sim_imitation_learning](https://github.com/ABC-iRobotics/isaac_sim_imitation_learning/tree/b558d358aac7cc02d7ec4eacd926c06e5c46682d) – ROS 2 nodes for launching Isaac Sim 4.5, and recording expert demonstrations using deterministic solvers and ground truth information.

## Authors
- András Makány – Master's student at Obuda University, Hungary (corresponding author)
- Prof. Dr. Péter Galambos – Vice Rector for Innovation at Obuda University, Hungary

## Citation (BibTeX)
```
@INPROCEEDINGS{11205394,
  author={Makány, András and Galambos, Péter},
  booktitle={2025 IEEE 23rd Jubilee International Symposium on Intelligent Systems and Informatics (SISY)}, 
  title={A Framework for Generating Synthetic Expert Demonstrations in Digital Twin-based Robot Learning}, 
  year={2025},
  volume={},
  number={},
  pages={000051-000056},
  doi={10.1109/SISY67000.2025.11205394}
}
```

## Acknowledgements
- This research was supported by the Consolidator Researcher Grant of Obuda University (Grant ID: OKPPKPC004). András Makány was supported by the 2024-2.1.1 (EKÖP) University Research Scholarship
- Program of the Ministry for Culture and Innovation from the source of the National Research, Development and Innovation Fund.Project 2024-1.2.3-HU-RIZONT-00069 has been implemented with support provided by the Ministry of Culture and Innovation of Hungary from the National Research, Development, and Innovation Fund, financed under the 2024-1.2.3-HU-RIZONT funding scheme.