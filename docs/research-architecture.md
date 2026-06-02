# Research Architecture

This document connects the research identity to the public GitHub organization.

## Research Identity

The central theme is structure-aware planning and control for mobile manipulation, where robot motion is designed not only to reach a target but also to actively acquire useful visual or spectral information under physical, geometric, sensing, and uncertainty constraints.

Initial application:

- line-scan-inspired RGB / hyperspectral scanning,
- mobile manipulator motion planning,
- visibility and coverage constraints,
- extensions toward state estimation, coverage planning, and uncertainty-aware control.

## Public Repository Graph

```text
research-reading-map
  -> line-scan-mobile-manipulator-demo
      -> ros2-moveit-grasping-demo
      -> ros2-mobile-robotics-labs
      -> robotics-control-learning-labs
      -> wmm-trajectory-tracking
      -> GTSAM_SLAM_VISION
      -> nerf-lab
  -> GTSAM_SLAM_VISION
      -> husky-gazebo-image-capture
      -> nerf-lab
  -> robotics-control-learning-labs
      -> wmm-trajectory-tracking
      -> Cruise_control
      -> RoboticScrewTheoryToolkit
      -> 3dof-robot-arm-report
```

## Repository Families

### 1. Active Scanning and Coverage

| Repo | Status | Purpose |
|---|---|---|
| [`line-scan-mobile-manipulator-demo`](https://github.com/WikiGenius/line-scan-mobile-manipulator-demo) | Public core, pinned | Main public scaffold for structure-aware line-scan / RGB-hyperspectral active scanning. |
| [`research-reading-map`](https://github.com/WikiGenius/research-reading-map) | Public core, pinned | Reading map and research architecture. |

Keep exact unpublished scanning algorithms, private datasets, calibration details, and paper ablations private.

### 2. Mobile Manipulation and ROS2 Systems

| Repo | Status | Purpose |
|---|---|---|
| [`ros2-moveit-grasping-demo`](https://github.com/WikiGenius/ros2-moveit-grasping-demo) | Public core, pinned | MoveIt2 grasping and Cartesian motion execution evidence. |
| [`ros2-mobile-robotics-labs`](https://github.com/WikiGenius/ros2-mobile-robotics-labs) | Public core, pinned | ROS2 mobile robotics lab scaffold. |
| [`hello_world_ros2_edx`](https://github.com/WikiGenius/hello_world_ros2_edx) | Public support | ROS2 learning/migration evidence. |

### 3. State Estimation, SLAM, and 3D Perception

| Repo | Status | Purpose |
|---|---|---|
| [`GTSAM_SLAM_VISION`](https://github.com/WikiGenius/GTSAM_SLAM_VISION) | Public core, pinned | Factor-graph visual SLAM and pose-estimation experiments. |
| [`husky-gazebo-image-capture`](https://github.com/WikiGenius/husky-gazebo-image-capture) | Public support | ROS2 Humble support node for Gazebo Husky image/odometry snapshot capture. |
| [`nerf-lab`](https://github.com/WikiGenius/nerf-lab) | Public support | NeRF, ray marching, view synthesis, and scene-representation intuition for active perception. |

### 4. Control, Dynamics, and Robot Math

| Repo | Status | Purpose |
|---|---|---|
| [`robotics-control-learning-labs`](https://github.com/WikiGenius/robotics-control-learning-labs) | Public core, pinned | State-space, LQR, observers, and public control labs. |
| [`wmm-trajectory-tracking`](https://github.com/WikiGenius/wmm-trajectory-tracking) | Public support | Whole-body mobile-manipulator tracking. |
| [`Cruise_control`](https://github.com/WikiGenius/Cruise_control) | Public support | MATLAB/Simulink control artifact. |
| [`RoboticScrewTheoryToolkit`](https://github.com/WikiGenius/RoboticScrewTheoryToolkit) | Public support | Screw theory, Jacobians, and kinematic foundations. |
| [`3dof-robot-arm-report`](https://github.com/WikiGenius/3dof-robot-arm-report) | Public support | Robot-arm modeling/control report. |

Private inverted-pendulum and uncertainty-aware control experiments should stay private until they are distilled into public examples.

## Public vs Private Rule

Public repos should show capability, clarity, and reproducible evidence. Private repos should protect publication value.

Public examples can include:

- simplified algorithms,
- synthetic scenes or toy data,
- baseline planners/controllers,
- tutorial-style derivations,
- screenshots, GIFs, and plots,
- report PDFs and citation links.

Private repos should keep:

- unpublished algorithms,
- private datasets,
- raw experiment logs,
- exact ablations and hyperparameters,
- paper drafts and reviewer-response work,
- sensitive applied CV/AI prototypes.

## Next Public Content Priorities

1. Add at least one figure or GIF to each pinned repo.
2. Add one runnable minimal example to the scaffold-heavy pinned repos.
3. Add a small bibliography and topic taxonomy here.
4. Convert private experiments into public distilled examples only when publication risk is low.
