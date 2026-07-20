# Restaurant Service Robot (ROS 2 Jazzy)

A simple Restaurant Service Robot modeled using URDF in ROS 2 Jazzy.

## Features
- Differential drive
- Two drive wheels
- Three caster wheels
- Camera
- LiDAR
- Top tray
- RViz visualization

## Folder Structure

```
restaurant_robot/
├── launch/
├── urdf/
├── images/
└── README.md
```

## Run

```bash
ros2 launch urdf_tutorial display.launch.py model:=/path/to/robot.urdf
```

Developed as part of my ROS 2 learning journey.
