---
title: "Drone Simulation Stack"
excerpt: "A simulation stack for autonomous drone racing built on ROS 2, Gazebo, PX4 Autopilot, MAVLink and QGroundControl — a base for vision-based gate detection and trajectory planning."
collection: portfolio
permalink: /portfolio/drone-simulation-stack/
date: 2025-09-01

# --- MEDIA (uncomment & fill after uploading files to images/projects/drone-simulation-stack/) ---
# header:
#   teaser: projects/drone-simulation-stack/cover.jpg
# video_url: https://www.youtube.com/embed/VIDEO_ID
# video_file: projects/drone-simulation-stack/demo.mp4
# gallery:
#   - image_path: projects/drone-simulation-stack/1.jpg
#     url: projects/drone-simulation-stack/1.jpg
#     title: "Gazebo simulation"
#   - image_path: projects/drone-simulation-stack/2.jpg
#     url: projects/drone-simulation-stack/2.jpg
#     title: "QGroundControl"
---

**Role:** Robotics / simulation engineer · **Year:** 2025 · **Stack:** ROS 2, Gazebo, PX4 Autopilot, MAVLink, QGroundControl

## Overview

A simulation stack for **autonomous drone racing**, built to develop and test flight-control code entirely in simulation before touching real hardware.

## What I built

- Set up the **simulated flight-control environment** for code-driven experiments.
- Integrated **PX4 Autopilot**, the **MAVLink** bridge, and **QGroundControl** into one working simulation workflow.
- Scoped the next milestones: **virtual gate detection with OpenCV** and **trajectory planning** in simulation.

## Demo

{% if page.video_url or page.video_file %}{% include video.html %}{% else %}*🎥 Video demo coming soon — drop a clip into `images/projects/drone-simulation-stack/` and set `video_url`/`video_file` in the front matter.*{% endif %}

## Gallery

{% if page.gallery %}{% include gallery caption="Autonomous drone racing simulation stack." %}{% else %}*📸 Screenshots coming soon.*{% endif %}
