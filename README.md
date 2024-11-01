# ECE-M202A-Final-Project
# Unitree Go 2 Autonomous Exploration and Object Retrieval System

## Overview
This project utilizes the Unitree Go 2 robot dog to autonomously explore designated areas, recognize and log objects in the environment using machine learning, and assist operators by retrieving specific items upon request. The project aims to reduce the manual workload and enhance safety in complex or hazardous environments, such as industrial facilities, warehouses, and emergency scenarios.

The system is controlled via a laptop and a mounted Raspberry Pi with a mobile battery pack to ensure portability and usability in various settings.

## Project Goals
### Problem Statement
Manual search and retrieval in complex or hazardous environments are often inefficient and risky. Existing methods relying on human effort are time-consuming, prone to error, and expose people to potential dangers, especially in scenarios like disaster response or large industrial facilities. The core challenges addressed in this project include:
- Efficient navigation through complex terrains
- Accurate object recognition and localization
- Safe and intuitive guidance for human operators

### Existing Solutions
While autonomous robots for navigation and object recognition are available, they often lack effective human-robot collaboration capabilities. Many systems focus solely on autonomous navigation, lacking the adaptability needed in uncertain environments or requiring constant human supervision, which limits their potential.

### Proposed Solution
This project proposes an integrated human-robot collaboration system where the Unitree Go 2 uses machine learning for dynamic object recognition and environment mapping. The robot autonomously explores areas, identifies objects, and reports them to the operator. Through simple voice commands, the operator can request specific items, allowing the robot to locate and guide the operator, enhancing operational efficiency and reducing risks.

## System Architecture
- **Platform**: Unitree Go 2 Robot Dog
- **Software Framework**: ROS 2 for modular and scalable software architecture
- **Components**:
  - **Navigation**: Autonomous exploration and mapping of the environment
  - **Object Recognition**: Machine learning models for identifying objects in real-time
  - **Human-Robot Interaction**: Voice command interface for intuitive operator control
  - **Portable Control Unit**: Raspberry Pi and mobile battery pack mounted on the robot

## Use Cases
### Example 1: Emergency Evacuation Support
In case of a building fire, the robot can guide victims to safety by identifying open pathways and emergency exits, memorizing routes, and providing verbal directional guidance. It can also communicate with first responders to alert them to victims needing medical assistance or unable to move, ensuring rapid response in critical situations.

### Example 2: Industrial Inspection and Tool Retrieval
In large industrial facilities, maintenance workers may need to retrieve specific tools across expansive or hazardous areas. The robot autonomously explores the area, logs tools, and allows operators to request specific items via voice command. The robot can guide workers to the required tools, reducing retrieval time and minimizing exposure to potential hazards.

## Getting Started
### Prerequisites
- **Hardware**: Unitree Go 2 robot dog, Raspberry Pi, mobile battery pack
- **Software**: ROS 2, Python, machine learning libraries for object recognition (e.g., OpenCV, TensorFlow or PyTorch), voice recognition software (e.g., Google Speech Recognition API)

### Installation
1. **Set up ROS 2** on the control terminal and Raspberry Pi.
2. **Install object recognition libraries** on the Raspberry Pi:
   ```bash
   sudo apt-get install python3-opencv
   pip install tensorflow
