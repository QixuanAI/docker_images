# This is an auto generated Dockerfile for ros:desktop-full
# generated from docker_images/create_ros_image.Dockerfile.em
FROM osrf/ros:noetic-desktop-buster

# label ros packages
LABEL sha256.ros-noetic-desktop-full=6a3f71573b2477e1b74c32c2439259991dfc82d64bfdb7f541edcfcd6aafbec2

# install ros packages
RUN apt-get update && apt-get install -y --no-install-recommends \
    ros-noetic-desktop-full=1.5.0-1* \
    && rm -rf /var/lib/apt/lists/*

