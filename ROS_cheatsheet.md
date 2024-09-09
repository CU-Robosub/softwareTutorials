# ROS2 Shell Command Cheat Sheet

- Initialize ROS2 Workspace
  `source /opt/ros/<distro>/setup.bash`

- Create a New ROS2 Package
  `ros2 pkg create <package_name> --build-type ament_cmake`

- Build the ROS2 Workspace (do this in the root of the repository)
  `colcon build`

- Source the Workspace
  `./install/setup.bash`

- Run a Node
  `ros2 run <package_name> <node_name>`

- List Available Nodes
  `ros2 node list`

- Show Node Information
  `ros2 node info <node_name>`

- List Topics
  `ros2 topic list`

- Echo Topic Data
  `ros2 topic echo <topic_name>`

- Publish to a Topic
  `ros2 topic pub <topic_name> <message_type> "{data: <value>}"`

- List Services
  `ros2 service list`

- Call a Service
  `ros2 service call <service_name> <service_type> "{data: <value>}"`

- List Parameters
  `ros2 param list`

- Get Parameter Value
  `ros2 param get <node_name> <parameter_name>`

- Set Parameter Value
  `ros2 param set <node_name> <parameter_name> <value>`

- Record Topics
  `ros2 bag record <topic_name>`

- Play Recorded Bag File
  `ros2 bag play <bag_file>`

- Launch a ROS2 Launch File
  `ros2 launch <package_name> <launch_file>`# ROS2 Shell Command Cheat Sheet

- Initialize ROS2 Workspace
  `source /opt/ros/<distro>/setup.bash`

- Create a New ROS2 Package
  `ros2 pkg create <package_name> --build- type ament_cmake`

- Build the ROS2 Workspace (do this in the root of the repository)
  `colcon build`

- Source the Workspace
  `./install/setup.bash`

- Run a Node
  `ros2 run <package_name> <node_name>`

- List Available Nodes
  `ros2 node list`

- Show Node Information
  `ros2 node info <node_name>`

- List Topics
  `ros2 topic list`

- Echo Topic Data
  `ros2 topic echo <topic_name>`

- Publish to a Topic
  `ros2 topic pub <topic_name> <message_type> "{data: <value>}"`

- List Services
  `ros2 service list`

- Call a Service
  `ros2 service call <service_name> <service_type> "{data: <value>}"`

- List Parameters
  `ros2 param list`

- Get Parameter Value
  `ros2 param get <node_name> <parameter_name>`

- Set Parameter Value
  `ros2 param set <node_name> <parameter_name> <value>`

- Record Topics
  `ros2 bag record <topic_name>`

- Play Recorded Bag File
  `ros2 bag play <bag_file>`

- Launch a ROS2 Launch File
  `ros2 launch <package_name> <launch_file>`
