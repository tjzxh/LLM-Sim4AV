# 基于大语言模型的自动驾驶测试：文献合集

## 目录
- [简介](#简介)
- [按模拟目标分类](#按模拟目标分类)
  - [1. 视觉信号生成](#1-视觉信号生成)
  - [2. 具体场景程序](#2-具体场景程序)
  - [3. 轨迹生成](#3-轨迹生成)
  - [4. 地图与轨迹](#4-地图与轨迹)

## 简介
本仓库收集了专注于大语言模型(LLM)在自动驾驶测试和模拟中应用的前沿研究论文。这些论文按其模拟目标进行分类，为不同研究方法提供了系统的概览。

## 按模拟目标分类

### 1. 视觉信号生成
专注于生成视觉输出（下一帧图像、真实感3D场景、驾驶视频）的论文：

- **ADriver-I**: "ADriver-I: A General World Model for Autonomous Driving" (Jia et al., 2023)
  - **输出类型**：下一帧图像
  - **简述**：ADriver-I是一个整合多模态大语言模型(MLLM)和视频扩散模型(VDM)的自动驾驶世界模型

- **ChatSim**: "ChatSim: Editable Scene Simulation for Autonomous Driving via Collaborative LLM-Agents" (Wei et al., 2024)
  - **输出类型**：真实感3D驾驶场景
  - **简述**：ChatSim通过语言命令实现可编辑的3D驾驶场景模拟
  - **GitHub**: [https://github.com/yifanlu0227/ChatSim](https://github.com/yifanlu0227/ChatSim)

- **DriveDreamer-2**: "DriveDreamer-2: LLM-Enhanced World Models for Driving Video Generation" (Zhao et al., 2024)
  - **输出类型**：驾驶视频
  - **简述**：DriveDreamer-2生成用户自定义的驾驶视频，用于训练驾驶感知方法
  - **项目主页**: [https://drivedreamer2.github.io](https://drivedreamer2.github.io)

### 2. 具体场景程序
专注于生成可执行模拟场景的论文：

- **Chat2Scenario**: "Chat2Scenario: Scenario Extraction from Dataset through LLM" (Zhao et al., 2024)
  - **输出类型**：Esmini和CarMaker场景
  - **简述**：Chat2Scenario使用LLMs从数据集中提取驾驶场景，提高了场景提取效率
  - **GitHub**: [https://github.com/ftgTUGraz/Chat2Scenario](https://github.com/ftgTUGraz/Chat2Scenario)

- **ChatScene**: "ChatScene: Safety-Critical Scenario Generation for Autonomous Vehicles" (Zhang et al., 2024)
  - **输出类型**：CARLA模拟
  - **简述**：ChatScene使用LLMs生成安全关键场景，提高车辆碰撞率15%
  - **GitHub**: [https://github.com/javyduck/ChatScene](https://github.com/javyduck/ChatScene)

- **ChatSUMO**: "ChatSUMO: LLM-based Traffic Simulation Tool" (Li et al., 2024)
  - **输出类型**：SUMO模拟
  - **简述**：ChatSUMO使用OpenStreetMap数据和LLM输入处理简化交通模拟生成

- **LEADE**: "LEADE: An LLM-enhanced Multi-objective Evolutionary Search for Autonomous Driving Test Scenario Generation" (Tian et al., 2024)
  - **输出类型**：具体场景程序
  - **简述**：LEADE为自动驾驶系统(ADS)测试生成多样化的安全关键场景

- **Natural-language-driven Simulation**: "Natural-language-driven Simulation Benchmark and Copilot for Efficient Production of Object Interactions in Virtual Road Scenes" (Yang et al., 2024)
  - **输出类型**：SVL场景
  - **简述**：使用包含120,000个虚拟道路场景的L2I基准数据集

- **Open-TI**: "Open-TI: Open Traffic Intelligence with Augmented Language Model" (Da et al., 2024)
  - **输出类型**：SUMO/CityFlow/CBEngine场景
  - **简述**：使用LLMs增强交通分析，架起产业界学术界的桥梁并支持模拟
  - **GitHub**: [https://github.com/DaRL-LibSignal/OpenTI](https://github.com/DaRL-LibSignal/OpenTI)

### 3. 轨迹生成
专注于生成交通轨迹的论文：

- **CTG++**: "CTG++: Language-Guided Traffic Simulation via Scene-Level Diffusion" (Zhong et al., 2023)
  - **输出类型**：轨迹
  - **简述**：CTG++通过场景级扩散模型实现基于用户查询的真实交通模拟

- **InteractTraj**: "InteractTraj: Language-Driven Interactive Traffic Trajectory Generation" (Xia et al., 2024)
  - **输出类型**：轨迹
  - **简述**：InteractTraj从自然语言描述生成交互式交通轨迹
  - **GitHub**: [https://github.com/X1a-jk/InteractTraj.git](https://github.com/X1a-jk/InteractTraj.git)

- **ProSim**: "Promptable Closed-loop Traffic Simulation" (Tan et al., 2024)
  - **输出类型**：轨迹
  - **简述**：ProSim是一个支持复杂用户提示的可提示闭环交通模拟框架
  - **GitHub**: [https://ariostgx.github.io/ProSim/](https://ariostgx.github.io/ProSim/)

- **SeGPT**: "ChatGPT-Based Scenario Engineer: A New Framework on Scenario Generation for Trajectory Prediction" (Li et al., 2024)
  - **输出类型**：轨迹
  - **简述**：SeGPT利用ChatGPT生成多样化和复杂的驾驶场景用于轨迹预测

- **Controllable Traffic Simulation**: "Controllable Traffic Simulation through LLM-Guided Hierarchical Chain-of-Thought Reasoning" (Liu et al., 2024)
  - **输出类型**：轨迹
  - **简述**：提出使用LLM引导的层次化思维链推理的交通模拟新框架

### 4. 地图与轨迹
专注于同时生成地图和轨迹的论文：

- **LCTGen**: "LCTGen: Language Conditioned Traffic Generation" (Tan et al., 2023)
  - **输出类型**：地图和轨迹
  - **简述**：LCTGen使用语言条件模型生成真实的交通场景
  - **项目主页**: [https://ariostgx.github.io/lctgen](https://ariostgx.github.io/lctgen)

- **LLMScenario**: "LLMScenario: Large Language Model Driven Scenario Generation" (Chang et al., 2024)
  - **输出类型**：地图和轨迹
  - **简述**：提出使用LLMs进行场景生成的LLMScenario，解决罕见角落场景问题

- **OmniTester**: "Multimodal Large Language Model Driven Scenario Testing for Autonomous Vehicles" (Lu et al., 2024)
  - **输出类型**：地图和轨迹
  - **简述**：OmniTester生成多样化的测试场景，增强可控性和真实性


# LLM-Based Autonomous Driving Testing: A Literature Collection

## Table of Contents
- [Introduction](#introduction)
- [Categories by Simulation Objective](#categories-by-simulation-objective)
  - [1. Visual Signal Generation](#1-visual-signal-generation)
  - [2. Concrete Scenario Program](#2-concrete-scenario-program)
  - [3. Trajectory Generation](#3-trajectory-generation)
  - [4. Map and Trajectories](#4-map-and-trajectories)
- [Contributing](#contributing)

## Introduction
This repository serves as a curated collection of cutting-edge research papers focusing on Large Language Model (LLM) applications in autonomous driving testing and simulation. The papers are categorized by their simulation objectives, providing a structured view of different approaches in the field.

## Categories by Simulation Objective

### 1. Visual Signal Generation
Papers focusing on generating visual outputs (next frame photos, photo-realistic 3D scenes, driving videos):

- **ADriver-I**: "ADriver-I: A General World Model for Autonomous Driving" (Jia et al., 2023)
  - **Output**: Next frame photo
  - **TL;DR**: ADriver-I is a world model integrating multimodal large language models (MLLM) and video diffusion models (VDM) for autonomous driving

- **ChatSim**: "ChatSim: Editable Scene Simulation for Autonomous Driving via Collaborative LLM-Agents" (Wei et al., 2024)
  - **Output**: Photo-realistic 3D driving scene
  - **TL;DR**: ChatSim enables editable 3D driving scene simulations through language commands
  - **GitHub**: [https://github.com/yifanlu0227/ChatSim](https://github.com/yifanlu0227/ChatSim)

- **DriveDreamer-2**: "DriveDreamer-2: LLM-Enhanced World Models for Driving Video Generation" (Zhao et al., 2024)
  - **Output**: Driving video
  - **TL;DR**: DriveDreamer-2 generates user-customized driving videos for training driving perception methods
  - **Project Page**: [https://drivedreamer2.github.io](https://drivedreamer2.github.io)

### 2. Concrete Scenario Program
Papers focusing on generating executable simulation scenarios:

- **Chat2Scenario**: "Chat2Scenario: Scenario Extraction from Dataset through LLM" (Zhao et al., 2024)
  - **Output**: Scenarios in Esmini and CarMaker
  - **TL;DR**: Chat2Scenario extracts driving scenarios from datasets using LLMs, improving scenario extraction efficiency
  - **GitHub**: [https://github.com/ftgTUGraz/Chat2Scenario](https://github.com/ftgTUGraz/Chat2Scenario)

- **ChatScene**: "ChatScene: Safety-Critical Scenario Generation for Autonomous Vehicles" (Zhang et al., 2024)
  - **Output**: CARLA simulations
  - **TL;DR**: ChatScene generates safety-critical scenarios using LLMs, improving vehicle collision rate by 15%
  - **GitHub**: [https://github.com/javyduck/ChatScene](https://github.com/javyduck/ChatScene)

- **ChatSUMO**: "ChatSUMO: LLM-based Traffic Simulation Tool" (Li et al., 2024)
  - **Output**: SUMO simulations
  - **TL;DR**: ChatSUMO simplifies traffic simulation generation using Open-StreetMap data and LLM input processing

- **LEADE**: "LEADE: An LLM-enhanced Multi-objective Evolutionary Search for Autonomous Driving Test Scenario Generation" (Tian et al., 2024)
  - **Output**: Concrete Scenario Program
  - **TL;DR**: LEADE generates diverse safety-critical scenarios for Autonomous Driving Systems (ADS) testing

- **Natural-language-driven Simulation**: "Natural-language-driven Simulation Benchmark and Copilot for Efficient Production of Object Interactions in Virtual Road Scenes" (Yang et al., 2024)
  - **Output**: SVL scenarios
  - **TL;DR**: Uses the L2I benchmark dataset containing 120,000 virtual road scenes across various topologies

- **Open-TI**: "Open-TI: Open Traffic Intelligence with Augmented Language Model" (Da et al., 2024)
  - **Output**: SUMO/CityFlow/CBEngine scenarios
  - **TL;DR**: Enhances traffic analysis using LLMs, bridging industry-academic gaps and supporting simulations
  - **GitHub**: [https://github.com/DaRL-LibSignal/OpenTI](https://github.com/DaRL-LibSignal/OpenTI)

### 3. Trajectory Generation
Papers focusing on generating traffic trajectories:

- **CTG++**: "CTG++: Language-Guided Traffic Simulation via Scene-Level Diffusion" (Zhong et al., 2023)
  - **Output**: Trajectories
  - **TL;DR**: CTG++ enables realistic traffic simulations guided by user queries through a scene-level diffusion model

- **InteractTraj**: "InteractTraj: Language-Driven Interactive Traffic Trajectory Generation" (Xia et al., 2024)
  - **Output**: Trajectories
  - **TL;DR**: InteractTraj generates interactive traffic trajectories from natural language descriptions
  - **GitHub**: [https://github.com/X1a-jk/InteractTraj.git](https://github.com/X1a-jk/InteractTraj.git)

- **ProSim**: "Promptable Closed-loop Traffic Simulation" (Tan et al., 2024)
  - **Output**: Trajectories
  - **TL;DR**: ProSim is a promptable framework for realistic traffic simulation, supporting complex user prompts
  - **GitHub**: [https://ariostgx.github.io/ProSim/](https://ariostgx.github.io/ProSim/)

- **SeGPT**: "ChatGPT-Based Scenario Engineer: A New Framework on Scenario Generation for Trajectory Prediction" (Li et al., 2024)
  - **Output**: Trajectories
  - **TL;DR**: SeGPT leverages ChatGPT to generate diverse and complex driving scenarios for trajectory prediction

- **Controllable Traffic Simulation**: "Controllable Traffic Simulation through LLM-Guided Hierarchical Chain-of-Thought Reasoning" (Liu et al., 2024)
  - **Output**: Trajectories
  - **TL;DR**: Proposes a novel framework for traffic simulation using LLM-guided hierarchical reasoning

### 4. Map and Trajectories
Papers focusing on both map and trajectory generation:

- **LCTGen**: "LCTGen: Language Conditioned Traffic Generation" (Tan et al., 2023)
  - **Output**: Map and trajectories
  - **TL;DR**: LCTGen generates realistic traffic scenarios using a language-conditioned model
  - **Project Page**: [https://ariostgx.github.io/lctgen](https://ariostgx.github.io/lctgen)

- **LLMScenario**: "LLMScenario: Large Language Model Driven Scenario Generation" (Chang et al., 2024)
  - **Output**: Map and trajectories
  - **TL;DR**: Proposes LLMScenario for scenario generation using LLMs, addressing rare corner scenarios

- **OmniTester**: "Multimodal Large Language Model Driven Scenario Testing for Autonomous Vehicles" (Lu et al., 2024)
  - **Output**: Map and trajectories
  - **TL;DR**: OmniTester generates diverse scenarios for testing, enhancing controllability and realism

## Contributing
We welcome contributions to this collection! Please feel free to submit pull requests with:
- New relevant papers
- Updates to existing paper information
- Additional resources or implementations
- Corrections or improvements to descriptions

