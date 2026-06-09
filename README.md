# megarover_common

Shared configuration and visualization assets for Megarover sim/real workspaces.

## Contents

- `configs/`
  - FastDDS profile without shared memory
  - robot_localization EKF parameter files
- `rviz/`
  - shared RViz layouts for Megarover and ZED point cloud inspection
- `nav2/`
  - shared high-level Nav2 controller/planner/costmap parameter files

## Intended use

- `megarover_sim` and `megarover_real` should mount this repository into their containers or source trees.
- Keep shared ROS parameters, shared high-level Nav2 settings, and RViz layouts here.
- Keep Isaac-only, hardware-only, and environment-specific launch logic in the per-workspace repositories.
