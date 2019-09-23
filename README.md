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
   * [Use Reinforcement Learning to train an autonomous driving agent in CARLA Simulator](https://github.com/zhangfuyang/rl_CARLA) - version 0.8.2
   * [Autonomous Driving on Carla simulator using Deep Deterministic Policy Gradients](https://github.com/ankur-rc/autodrive_ddpg) - version 0.8.2
   * [CIRL: Controllable Imitative Reinforcement Learning for Vision-based Self-driving ](https://github.com/HubFire/Muti-branch-DDPG-CARLA) - version 0.8.2(seems)
   * [customized PPO based agent for Carla](https://github.com/bitsauce/Carla-ppo) - version 0.9.5
   * [Reinforcement Learning Environment for CARLA Autonomous Driving Simulator](https://github.com/GokulNC/Setting-Up-CARLA-Reinforcement-Learning) - version 0.8.0
   * [Reinforcement Learning Coach by Intel AI Lab](https://github.com/NervanaSystems/coach) - Work with version version 0.8.4
   * [What is candy? A model with the structure: Hierarchical Observation -- Plan&Policy -- Hierarchical Actions](https://github.com/createamind/candy) - 0.8.2 
   * [Reinforcement Learning codebase for self-driving car in Carla](https://github.com/Sentdex/Carla-RL) - version 0.9.5
     
   ### Imitation Learning 🌈 <a name="IL" /> 
   * [Training framework for conditional imitation learning](https://github.com/felipecode/coiltraine)
   * [Carla Imitation Learning Trainer](https://github.com/mvpcom/carlaILTrainer)
   * [A pytorch implementation to train the conditional imitation learning policy](https://github.com/onlytailei/carla_cil_pytorch)
   
  
   ### Multi-Agent <a name="MA" />🌄
   * [Learning Environments for Multi-Agent Connected Autonomous Driving (MACAD)](https://github.com/praveen-palanisamy/macad-gym)
   
   
   ### Other <a name="Other_Code" />🚦
   * [Hands-On-Intelligent-Agents-with-OpenAI-Gym](https://github.com/PacktPublishing/Hands-On-Intelligent-Agents-with-OpenAI-Gym)
   * [Self Driving Cars Longitudinal and Lateral Control Design](https://github.com/enginBozkurt/SelfDrivingCarsControlDesign)
   * [The OmniScape Dataset](https://github.com/ARSekkat/OmniScape)
   * [Module for deep learning powered, stateful imitation learning in the CARLA autonomous vehicle simulator. ](https://github.com/affinis-lab/core)
   * [Module for car detection](https://github.com/affinis-lab/car-detection-module)
   * [Module for detecting traffic lights in the CARLA](https://github.com/affinis-lab/traffic-light-detection-module)
   * [Implementing Lane Keeping Assist (LKA) on CARLA simulator](https://github.com/paulyehtw/Lane-Keeping-Assist-on-CARLA)
   * [Similar Simulator](https://github.com/sigmaai/self-driving-golf-cart)
   * [Generating training data from the Carla driving simulator in the KITTI dataset format](https://github.com/enginBozkurt/carla-training-data)
   * [Small example for loading the CARLA data from the PRECOG paper](https://github.com/nrhine1/precog_carla_dataset)
   * [A scenario loader for the automotive simulator](https://github.com/MrMushroom/CarlaScenarioLoader) - Carla 0.9.3
   * [My playground with Carla](https://github.com/kvasnyj/carla) - version 0.8.x
   
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
