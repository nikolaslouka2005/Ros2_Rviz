# ROS 2 RViz Robot Visualization

This project demonstrates a simple robot model described using URDF and visualized in RViz, using ROS 2 Jazzy on Ubuntu.

The model includes basic geometric shapes and TF frames, and is visualized via the `urdf_tutorial` launch system.

---

## 📁 Contents

| File                   | Description                                 |
|------------------------|---------------------------------------------|
| `my_robot.urdf`        | The URDF file that defines the robot model |
| `rviz_robot_model.png` | Screenshot showing the full robot in RViz  |
| `rviz_tf_tree.png`     | Screenshot showing the robot's TFs in RViz |

---

## 🚀 How to Launch the Model

Ensure that ROS 2 Jazzy is installed and sourced, and that the `urdf_tutorial` package is available.

Run the following command to launch the robot in RViz:

```bash
ros2 launch urdf_tutorial display.launch.py model:=/home/nikolas-louka/my_robot_rviz_demo/my_robot.urdf

