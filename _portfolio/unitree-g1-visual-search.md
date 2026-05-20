---
title: "Autonomous Visual Search Pipeline for Unitree G1"
excerpt: "Perception-and-control pipeline that lets a Unitree G1 humanoid find a target object, align to it, approach, and stop — built in MuJoCo with OpenCV and a finite-state controller."
collection: portfolio
permalink: /portfolio/unitree-g1-visual-search/
date: 2026-04-01

# --- MEDIA (uncomment & fill after uploading files to images/projects/unitree-g1-visual-search/) ---
# header:
#   teaser: projects/unitree-g1-visual-search/cover.jpg
# video_url: https://www.youtube.com/embed/VIDEO_ID      # YouTube/Vimeo EMBED url
video_file: projects/unitree-g1-visual-search/demo.mp4
# gallery:
#   - image_path: projects/unitree-g1-visual-search/1.jpg
#     url: projects/unitree-g1-visual-search/1.jpg
#     title: "Target detection (HSV + contours)"
#   - image_path: projects/unitree-g1-visual-search/2.jpg
#     url: projects/unitree-g1-visual-search/2.jpg
#     title: "Approach behavior in MuJoCo"
---

**Role:** Robotics software engineer · **Year:** 2026 · **Stack:** C++, MuJoCo, OpenCV, unitree_sdk2, DDS, YAML, CMake

## Overview

An autonomous search-and-navigation pipeline for a **Unitree G1 humanoid robot**, developed in **MuJoCo** simulation. The robot locates a target object in a structured indoor scene, centers on it, walks toward it, and stops at close range — fully driven by onboard vision.

## What I built

- Designed an end-to-end **perception-and-control workflow**: locate the target → align to it → approach → stop at close range.
- Implemented **object detection in OpenCV** using HSV color filtering, contour-based extraction, and image-space centering logic.
- Built a **finite-state controller (FSM)** with explicit *search*, *align*, *approach*, and *stop* states for predictable behavior.
- Integrated **depth-based distance estimation** and **DDS communication** with the Unitree locomotion control stack to translate vision into gait commands.

## Demo

{% if page.video_url or page.video_file %}{% include video.html %}{% else %}*🎥 Video demo coming soon — drop a clip into `images/projects/unitree-g1-visual-search/` and set `video_url`/`video_file` in the front matter.*{% endif %}

## Gallery

{% if page.gallery %}{% include gallery caption="Autonomous visual search on Unitree G1 in MuJoCo." %}{% else %}*📸 Screenshots coming soon.*{% endif %}
