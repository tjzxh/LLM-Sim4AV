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

