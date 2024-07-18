# realsense_rgbd_transport_ros2

## Dependencies
### Realsense SDK
```bash
. /opt/ros/humble/setup.bash
sudo apt install ros-${ROS_DISTRO}-realsense2-camera -y
sudo apt install ros-${ROS_DISTRO}-compressed-image-transport
```

## Usage
```bash
ros2 run realsense_rgbd_transport_ros2 rgbd_pub
ros2 run realsense_rgbd_transport_ros2 rgbd_sub
ros2 run realsense_rgbd_transport_ros2 rgbd_sub_compressed
```
