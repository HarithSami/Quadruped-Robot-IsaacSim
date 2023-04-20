# NVIDIA Omniverse Robot Simulation and Training with Petoi Bittle Robot and Isaac Sim
This is a project that showcases how to simulate and train a Petoi Bittle robot using NVIDIA Omniverse, Isaac Sim, and Isaac Gym. The Petoi Bittle robot is a four-legged robot that can walk, turn, and perform other actions. The project includes the 3D meshes and URDF files for the Petoi Bittle robot.

![110247158-c9636d80-7fa5-11eb-92ab-4f71c79b052b](https://user-images.githubusercontent.com/66371106/233337451-480db6a7-c0c6-4dbe-9f0c-1d4c73d26584.png)

# Requirements
• NVIDIA Omniverse (version 2022.1 or higher)
• NVIDIA Isaac Sim (version 2022.1 or higher)
• NVIDIA Isaac Gym (version 2022.1 or higher)
• Joint Monkey plugin for Isaac Sim
• PyTorch (version 1.9 or higher)
• NumPy (version 1.19 or higher)

# Usage
• Open the Petoi Bittle robot simulation scene in NVIDIA Omniverse
• Use Joint Monkey plugin to create a new trajectory for the robot and record it
• Use Isaac Gym to train the robot to follow the trajectory using the TD3 algorithm
• Visualize the training progress using the included forked TD3 benchmarking code

# Results
The Petoi Bittle robot should learn to follow the trajectory and perform other actions such as turning and walking. You can visualize the training progress using the included TD3 benchmarking code.

# Credits
This project uses the Petoi Bittle robot 3D meshes and URDF files from the official Petoi Bittle GitHub repository. The TD3 benchmarking code is based on the official NVIDIA Isaac Gym benchmarking code.

# License
This project is licensed under the MIT License - see the LICENSE.md file for details.
