# Soubgroup B3: AR-Based Digital Twin Teleoperation in Simulation

## Assignment 3: Gesture-Based AR Control Framework for UR5e Digital Twin Using Hand Tracking (SIMULATION EXPERIMENT)

### What to do: Investigate whether an industrial robot manipulator can be intuitively controlled in Augmented Reality through gesture-based interaction with a simulated digital twin, using AR spatial anchoring and real-time motion planning, without requiring a physical robot, and evaluate the usability and performance of AR teleoperation in a simulated robotics environment using the UR5e model.
1) Design an AR environment in Unity (or Unreal Engine) where a virtual model of the Universal Robots UR5e is overlaid onto a real workspace using spatial mapping (OpenXR-compatible AR device such as Magic Leap 2)
2) Import and configure the UR5e CAD/URDF model in a simulated robotics environment, ensuring correct kinematics, joint constraints, and alignment with the AR digital twin
3) Implement a real-time gesture-based interaction system using hand tracking: Select the robot end-effector using a defined gesture, Manipulate end-effector pose (position and orientation) in 3D space, Confirm motion commands through gesture release or selection input
4) Implement a real-time simulation pipeline using MoveIt 2: Convert AR interaction into Cartesian target poses, Perform inverse kinematics and trajectory planning, Execute planned motion in simulation
5) Integrate visualization and debugging tools using RViz to display robot state, planned trajectories, and execution results in real time
6) Ensure synchronization between AR digital twin and simulated robot state, maintaining consistent pose updates, coordinate frames, and motion timing
7) Design a user study (within-subjects) evaluating AR teleoperation performance: Task completion time, End-effector positioning accuracy, Path efficiency (trajectory deviation from optimal path), Motion smoothness (velocity stability / jerk analysis), User workload (NASA-TLX), Perceived intuitiveness and usability (Likert scales)
8) Collect and analyze both subjective (user feedback, usability ratings) and objective (trajectory logs, error metrics, completion times) data
9) Compare results against a baseline condition using traditional non-AR control methods (e.g., GUI-based control or RViz manual goal setting)

Software needed: Unity 2022 LTS or Unreal Engine, ROS 2, MoveIt 2, RViz, OpenXR-compatible AR device SDK (e.g., Magic Leap 2), Python for data analysis, R or JASP for statistics

Research needed: AR-based human-robot interaction, digital twin systems, gesture-based control interfaces, motion planning and inverse kinematics, spatial tracking and calibration methods, usability evaluation in robotics systems

Deliverables: AR application with UR5e digital twin, gesture-based control system in simulation, ROS2 + MoveIt 2 integration pipeline, full experimental protocol, raw dataset of user performance, statistical analysis report

# Starting point: 
- [Download Unity, use the unige email for the license](https://unity.com/products/unity-student)
- https://developer-docs.magicleap.cloud/docs/guides/developer-tools/ml-hub/magic-leap-hub/ Magic Leap 2 SDK -> download the Unity's packages from the ML Hub 2.0
