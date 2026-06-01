# Topic Taxonomy

This taxonomy organizes paper notes around the research identity.

## 1. Structure-Aware Active Scanning

Questions:

- How should a robot select viewpoints or trajectories to improve sensing quality?
- How should line-scan or push-broom sensing geometry affect planning?
- Which coverage metrics are meaningful for visual or spectral inspection?

Related public repo:

- [`line-scan-mobile-manipulator-demo`](https://github.com/WikiGenius/line-scan-mobile-manipulator-demo)

## 2. Mobile Manipulation and Whole-Body Planning

Questions:

- How should the mobile base and manipulator coordinate during inspection?
- How do reachability, collision constraints, and base placement affect scan feasibility?
- Which simplifications are acceptable for public demos?

Related public repos:

- [`ros2-moveit-grasping-demo`](https://github.com/WikiGenius/ros2-moveit-grasping-demo)
- [`wmm-trajectory-tracking`](https://github.com/WikiGenius/wmm-trajectory-tracking)
- [`ros2-mobile-robotics-labs`](https://github.com/WikiGenius/ros2-mobile-robotics-labs)

## 3. State Estimation, SLAM, and Uncertainty

Questions:

- How does pose uncertainty affect scan quality?
- Which factor-graph or SLAM methods are useful for visual state estimation?
- How can estimation quality be included in planning metrics?

Related public repos:

- [`GTSAM_SLAM_VISION`](https://github.com/WikiGenius/GTSAM_SLAM_VISION)
- [`orb_slam_demo`](https://github.com/WikiGenius/orb_slam_demo)

## 4. Control and Tracking

Questions:

- Which controllers are good baselines for mobile-manipulator motion?
- How do LQR, observers, and trajectory tracking connect to scan execution?
- What can be released publicly without exposing unpublished methods?

Related public repos:

- [`robotics-control-learning-labs`](https://github.com/WikiGenius/robotics-control-learning-labs)
- [`Cruise_control`](https://github.com/WikiGenius/Cruise_control)
- [`3dof-robot-arm-report`](https://github.com/WikiGenius/3dof-robot-arm-report)

## 5. 3D Perception and View Synthesis

Questions:

- How do ray geometry and view synthesis relate to active perception?
- Which scene representations help reason about coverage and reconstruction?
- How do neural representations compare with geometric SLAM for planning support?

Related public repo:

- [`nerf-lab`](https://github.com/WikiGenius/nerf-lab)

## Paper Note Tags

Use these tags consistently in future notes:

```text
active-perception
coverage-planning
line-scan
hyperspectral-imaging
mobile-manipulation
whole-body-control
state-estimation
factor-graphs
visual-slam
uncertainty-aware-control
nerf
view-synthesis
ros2
moveit2
```
