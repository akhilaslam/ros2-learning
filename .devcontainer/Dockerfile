FROM osrf/ros:humble-desktop-full

RUN apt-get update && apt-get install -y \
    python3-pip \
    python3-colcon-common-extensions \
    novnc \
    websockify \
    x11vnc \
    xvfb \
    && rm -rf /var/lib/apt-get/lists/*

ENV DISPLAY=:0
