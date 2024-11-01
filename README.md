# ECE-M202A-Final-Project - Unitree Go 2 Autonomous Exploration and Object Retrieval System

## Overview
This project utilizes the Unitree Go 2 robot dog to autonomously explore designated areas, recognize and log objects using machine learning, and assist operators by retrieving specific items upon request. The project is designed to improve operational efficiency and reduce risks in complex or hazardous environments, such as industrial facilities, warehouses, and emergency response scenarios.

The system is controlled through a laptop and includes a mounted Raspberry Pi with a mobile battery pack to ensure portability and usability in diverse settings.

## Project Goals
### Problem Statement
Manual search and retrieval tasks in complex environments can be inefficient and pose safety risks. Current methods relying on human effort are time-consuming, error-prone, and expose individuals to potential dangers, particularly in areas like search and rescue or large industrial facilities. The main challenges addressed in this project include:
- Efficient navigation through challenging terrains
- Accurate real-time object recognition and logging
- Safe and intuitive guidance for human operators

### Existing Solutions
Existing robotic solutions often focus solely on autonomous navigation or require constant human oversight, limiting flexibility and adaptability. These systems lack effective collaboration with human operators, reducing their usefulness in dynamic or unpredictable environments.

### Proposed Solution
This project aims to create a collaborative human-robot system where the Unitree Go 2 robot dog uses machine learning for object recognition and environment mapping. The robot autonomously explores an area, identifies objects, and reports back to the operator. Through a simple voice command interface, operators can then direct the robot to locate specific items, enhancing safety, reducing workload, and improving efficiency.

## Specific Aims
### Aim 1: Develop an Autonomous Exploration and Object Recognition System
- **Objective**: Equip the robot to autonomously explore areas, recognize objects in real-time, and log them for easy reporting.
- **Expected Outcome**: A reliable autonomous exploration system that accurately identifies and logs objects, usable in various environments.

### Aim 2: Enable Intuitive Human-Robot Collaboration through Voice Command Interface
- **Objective**: Provide a hands-free, voice-controlled interface allowing the operator to request specific objects and guide the robot’s actions in real-time.
- **Expected Outcome**: An intuitive interface enabling efficient operator collaboration with the robot.

### Aim 3: Implement Advanced Safety and Situational Awareness Features for Enhanced Operator Guidance
- **Objective**: Enhance safety and situational awareness to support navigation and risk reduction in hazardous or low-visibility environments.
- **Expected Outcome**: A system capable of safely guiding operators, improving situational awareness, and minimizing risks.

### Aim 4: Validate the System in Real-World Use Cases
- **Objective**: Test the system’s performance in real-world scenarios to meet functionality and safety standards in applications such as emergency evacuation and industrial tool retrieval.
- **Expected Outcome**: Proven effectiveness of the system in practical applications, providing insights for further optimization.

## System Architecture
- **Platform**: Unitree Go 2 robot dog
- **Software Framework**: ROS 2 for a modular, scalable architecture
- **Components**:
  - **Navigation**: Autonomous exploration and mapping capabilities
  - **Object Recognition**: Machine learning models for identifying objects in real-time
  - **Human-Robot Interaction**: Voice command interface for seamless operator control
  - **Portable Control Unit**: Raspberry Pi and mobile battery pack for enhanced portability

## Use Cases
### Example 1: Emergency Evacuation Support
In case of a building fire, the robot identifies emergency exits, remembers safe paths, and provides verbal guidance to assist people in reaching safety. The robot can also alert first responders about victims needing assistance, improving response time in critical situations.

### Example 2: Industrial Inspection and Tool Retrieval
In industrial facilities, the robot autonomously explores, logs tools, and allows operators to request specific items via voice command. This reduces retrieval time and minimizes human exposure to potentially hazardous areas.

## Getting Started
### Prerequisites
- **Hardware**: Unitree Go 2 robot, Raspberry Pi, mobile battery pack
- **Software**: ROS 2, Python, machine learning libraries (e.g., OpenCV, TensorFlow or PyTorch), voice recognition software (e.g., Google Speech Recognition API)
