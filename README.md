# Intelligence Cruise System

## Abstract
This project explores the more general adaptive cruise control system. Firstly, based on the PID control algorithm, this project develops a longitudinal controller and integrates several advanced driver assistance system functions: cruise function, following function, speed selection function, red light stop & go function, emergency brake system. The dynamic functions are integrated with each other to establish a reasonable multi-mode switching control strategy. In the development of the following function, in order to improve the following characteristics of the vehicle, a driver model based on the distance is introduced, so that the vehicle can simultaneously calculate the appropriate throttle opening by referring to the preceding vehicle speed and the ideal distance. This project designs a lateral controller for the adaptive cruise control system as well. By establishing a vehicle steering model, the lateral controller can refer to the angle between the heading angle of the vehicle and the target point to implement the steering control, and in addition, the vehicle can travel in the lane by means of the lateral controller. On this basis, this project integrates the functions of the vertical controller and the horizontal controller, and designs a high-speed overtaking function to enhance the passenger's user experience by simulating the driver's lane change and parallel operation.

Secondly, this project tests and improves the system based on the intelligent driving simulation platform CARLA. In the design process, this projects ummarizes the hierarchical structure of the CARLA simulator and its world view, and summarizes the test scenario construction process to prepare for the virtual test in the iterative development process.

Finally, based on the summarized scenario design process, this project builds multiple test scenarios and designs the corresponding test flow, and carries out virtual test experiments on the designed system. Through multiple experimental data analysis, the system designed in this project can integrate multiple assisted driving functions reasonably, and can switch different functions quickly and accurately under different working conditions, meeting the expected requirements. In addition, the virtual experiment-based development process provides a solution for rapid iteration, cost control and early troubleshooting of driving systems.

## Experiment Demo
<div align=center><img width="400" height="200" src="https://github.com/HanzhiC/CARLA-Intelligent-Cruise-System/blob/master/Image/4.png"/></div>
<div align=center><img width="400" height="200" src="https://github.com/HanzhiC/CARLA-Intelligent-Cruise-System/blob/master/Image/3.png"/></div>
<div align=center><img width="400" height="200" src="https://github.com/HanzhiC/CARLA-Intelligent-Cruise-System/blob/master/Image/2.png"/></div>
