# ROS 2 Workspace

This repository contains a ROS 2 workspace created by [Your Name].

## Overview

This ROS 2 workspace is set up to facilitate the development and organization of your robotic projects. It includes essential configurations and packages to kickstart your ROS 2 development.

## Getting Started

### Prerequisites

- [ROS 2 Humble](https://docs.ros.org/en/humble/Installation.html)
- [Colcon](https://colcon.readthedocs.io/en/released/user/installation.html)

### Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/AlexandruRO45/ros2_ws.git
    ```

2. Navigate to the workspace directory:

    ```bash
    cd ros2_ws
    ```

3. Build the workspace using colcon:

    ```bash
    colcon build
    ```

4. Source the setup file:

    ```bash
    source install/setup.bash
    ```

### Usage

- Launch the ROS 2 workspace:

    ```bash
    ros2 run [your_package_name] [your_launch_file_name]
    ```

## Directory Structure

- **src**: Contains ROS 2 packages.
- **build**: Default build directory for colcon.
- **install**: Default installation directory for colcon.
- **log**: Default log directory for ROS 2.


## Acknowledgments

This project is meant for my practise with ros2 in general, plus some additional packages that might be used for the Robo Cup 2024.

