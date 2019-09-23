# Awesome CARLA 💙 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of awesome CARLA tutorials, blogs, and related projects.

![alt text](http://carla.org//img/carla.jpg)

## 👉 Table of Contents <a name="TOC" />👈

<!-- MarkdownTOC depth=4 -->
* [Whats The CARLA](#whatsCarla)
* [Official Repositories](#official)
* [Tutorials](#tutorials)
* [SampleCodes/Projects](#sample)
    * [Reinforcement Learning](#RL)
    * [Imitation Learning](#IL)
    * [Multi-Agent](#MA)
    * [Other](#Other_Code)
* [Contribution](#contributions)
* [License](#License)
<!-- /MarkdownTOC --> 

<img src="imgs/downfinger.png" alt="down" width="250" height="150">


## Whats The CARLA ? 👀 <a name="whatsCarla" />

CARLA has been developed from the ground up to support development, training, and validation of autonomous driving systems. In addition to open-source code and protocols, CARLA provides open digital assets (urban layouts, buildings, vehicles) that were created for this purpose and can be used freely. The simulation platform supports flexible specification of sensor suites, environmental conditions, full control of all static and dynamic actors, maps generation and much more.
More info [here](http://carla.org/).

<a name="official" />

## Official Repositories 🏢 
* [Main source code](https://github.com/carla-simulator/carla)
* [Traffic scenario definition and execution engine](https://github.com/carla-simulator/scenario_runner) - Work with 0.9.2 and up
* [ROS bridge for CARLA Simulator](https://github.com/carla-simulator/ros-bridge) - Work with 0.9.4 and up
* [Reinforcement learning baseline agent trained with the Actor-critic (A3C) algorithm](https://github.com/carla-simulator/reinforcement-learning) - Work with 0.8.x versions only
* [Repository to store conditional imitation learning based AI that runs on CARLA](https://github.com/carla-simulator/imitation-learning) - Work with 0.8.x versions only
* [Repository to store different driving benchmarks that run on the CARLA simulator](https://github.com/carla-simulator/driving-benchmarks) - Work with 0.8.x versions only
* [Data collector, also contains an client side agent ](https://github.com/carla-simulator/data-collector) - Work with 0.8.x versions only
* [Standalone GUI application to enhance RoadRunner maps with traffic lights and traffic signs information](https://github.com/carla-simulator/carla-map-editor)
* [Integration of AutoWare AV software with the CARLA simulator](https://github.com/carla-simulator/carla-autoware) - Work with 0.9.6

[<img src="imgs/up.png" alt="down" width="30" height="30">  **Back to Top**](#TOC)    

## Tutorials <a name="tutorials" /> 📕 📘 📗 📓

* [Introduction to the CARLA simulator: training a neural network to control a car](https://medium.com/asap-report/introduction-to-the-carla-simulator-training-a-neural-network-to-control-a-car-part-1-e1c2c9a056a5)
* [Setting up CARLA Simulator for the Self-Driving Cars Specialization](https://medium.com/datadriveninvestor/setting-up-carla-simulator-for-the-self-driving-cars-specialization-d38d4f6a0486)
* [Official Doc](https://carla.readthedocs.io/en/latest/getting_started/)
* [Coursera(self-driving-cars)](https://www.coursera.org/specializations/self-driving-cars)
* [Model-free Deep Reinforcement Learning for Urban Autonomous Driving](https://www.groundai.com/project/model-free-deep-reinforcement-learning-for-urban-autonomous-driving/)

[<img src="imgs/up.png" alt="down" width="30" height="30">  **Back to Top**](#TOC) 

## Sample Codes / Projects <a name="sample" /> 🎉🎉🎉   

   ### Reinforcement Learning 🚧 <a name="RL" />
   * [Use Reinforcement Learning to train an autonomous driving agent in CARLA Simulator](https://github.com/zhangfuyang/rl_CARLA) - Use version 0.8.2
   * [Autonomous Driving on Carla simulator using Deep Deterministic Policy Gradients](https://github.com/ankur-rc/autodrive_ddpg) - Use version 0.8.2
   * [CIRL: Controllable Imitative Reinforcement Learning for Vision-based Self-driving ](https://github.com/HubFire/Muti-branch-DDPG-CARLA) - version 0.8.2(seems)
   * [customized PPO based agent for Carla](https://github.com/bitsauce/Carla-ppo) - Use version 0.9.5
   * [Reinforcement Learning Environment for CARLA Autonomous Driving Simulator](https://github.com/GokulNC/Setting-Up-CARLA-Reinforcement-Learning) - Use version 0.8.0
   * [Reinforcement Learning Coach by Intel AI Lab](https://github.com/NervanaSystems/coach) - Use version 0.8.4
   * [What is candy? A model with the structure: Hierarchical Observation -- Plan&Policy -- Hierarchical Actions](https://github.com/createamind/candy) - Use version 0.8.2 
   * [Reinforcement Learning codebase for self-driving car in Carla](https://github.com/Sentdex/Carla-RL) - Use version 0.9.5
   * [Double DQN to train an agent how to drive autonomously](https://github.com/koustavagoswami/Autonomous-Car-Driving-using-Deep-Reinforcement-Learning-in-Carla-Simulator)  - Use version 0.8.x (seems)
   
   ### Imitation Learning 🌈 <a name="IL" /> 
   * [Training framework for conditional imitation learning](https://github.com/felipecode/coiltraine) - Use version 0.8.x
   * [Carla Imitation Learning Trainer](https://github.com/mvpcom/carlaILTrainer) - Use version 0.8.x
   * [A pytorch implementation to train the conditional imitation learning policy](https://github.com/onlytailei/carla_cil_pytorch) - Use version 0.8.x (seems)
   
  
   ### Multi-Agent <a name="MA" />🌄
   * [Learning Environments for Multi-Agent Connected Autonomous Driving (MACAD)](https://github.com/praveen-palanisamy/macad-gym) - Use version 0.9.x
   
   
   ### Other <a name="Other_Code" />🚦
   * [Hands-On-Intelligent-Agents-with-OpenAI-Gym](https://github.com/PacktPublishing/Hands-On-Intelligent-Agents-with-OpenAI-Gym) - Use version 0.8.x
   * [Self Driving Cars Longitudinal and Lateral Control Design](https://github.com/enginBozkurt/SelfDrivingCarsControlDesign) - Use version  0.8.x
   * [The OmniScape Dataset](https://github.com/ARSekkat/OmniScape) - Use version 0.9.x
   * [Module for deep learning powered, stateful imitation learning in the CARLA autonomous vehicle simulator. ](https://github.com/affinis-lab/core) - Use version 0.8.4
   * [Module for car detection](https://github.com/affinis-lab/car-detection-module) - Use version 0.8.4
   * [Module for detecting traffic lights in the CARLA](https://github.com/affinis-lab/traffic-light-detection-module) - Use version 0.8.4
   * [Implementing Lane Keeping Assist (LKA) on CARLA simulator](https://github.com/paulyehtw/Lane-Keeping-Assist-on-CARLA) - Use version 0.8.x
   * [ROS bridge for CARLA simulator](https://github.com/sigmaai/self-driving-golf-cart/blob/master/ros/src/simulation/README.md) - Use version 0.9.2 and up
   * [Generating training data from the Carla driving simulator in the KITTI dataset format](https://github.com/enginBozkurt/carla-training-data) - Use version 0.8.x
   * [Small example for loading the CARLA data from the PRECOG paper](https://github.com/nrhine1/precog_carla_dataset) - Use version0.8.x (seems)
   * [A scenario loader for the automotive simulator](https://github.com/MrMushroom/CarlaScenarioLoader) - Use version 0.9.3
   * [My playground with Carla](https://github.com/kvasnyj/carla) - Use version 0.8.x
   * [Carla Simulator Data Collector (semantic segmentation)](https://github.com/enginBozkurt/CarlaSimulatorDataCollector) - Use version 0.8.4
   * [Image segmentation using U-Net](https://github.com/henyau/Image-Segmentation-with-Unet)
   * [Simulate precise LiDAR point cloud data from Carla](https://github.com/liuzuxin/Pesudo_Lidar_PointCloud_Carla) - Use version 0.9.6
   * [C++ Client for Unreal Engine 4 running Carla](https://github.com/p-schulz/CarlaClientCpp)
   * [Carla Display on Browser - Backend](https://github.com/mellocolate/carla-display-backend) - Use version 0.9.6
   * [Dockerfile to use CARLA ROS bridge on Docker container](https://github.com/atinfinity/carla_ros_bridge_docker) - Use version 0.9.6
   * [Generate visual navigation data for CARLA](https://github.com/IamWangYunKai/carla_py) - 0.9.5
   * [CARLA-Lane_Detection](https://github.com/angelkim88/CARLA-Lane_Detection) - Use version 0.9.6
   * [A traffic rules monitor for the CARLA simulator](https://github.com/abol-karimi/TrafficMonitor)
   
[<img src="imgs/up.png" alt="down" width="30" height="30">  **Back to Top**](#TOC) 
 
## Contributions 📭  <a name="contributions" />

Your contributions are always welcome!

If you want to contribute to this list (please do), send me a pull request
Also, if you notice that any of the above listed repositories should be deprecated, due to any of the following reasons:

* Repository's owner explicitly say that "this library is not maintained".
* Not committed for long time (2~3 years).

More info on the [guidelines](https://github.com/Amin-Tgz/awesome-CARLA/blob/master/contributing.md)

## License  <a name="License" />
Licensed under the [Creative Commons CC0 License](https://creativecommons.org/publicdomain/zero/1.0/).
