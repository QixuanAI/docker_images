# This is an auto generated Dockerfile for ros:desktop-full
# generated from docker_images/create_ros_image.Dockerfile.em
FROM osrf/ros:melodic-desktop-stretch

# label ros packages
LABEL sha256.ros-melodic-desktop-full=b65fec1171c245889a6097f7894d85c2d4884595ed2aa8ed0553303412c13ddd

# install ros packages
RUN apt-get update && apt-get install -y --no-install-recommends \
    ros-melodic-desktop-full=1.4.1-0* \
    && rm -rf /var/lib/apt/lists/*

