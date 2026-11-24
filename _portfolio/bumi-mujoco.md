---
title: "Noetix Bumi Humanoid — MuJoCo Simulator with a DDS Bridge"
excerpt: "A MuJoCo simulator for the Noetix Bumi humanoid that impersonates the robot's motion-control board over DDS, so unmodified SDK clients run against simulation."
collection: portfolio
permalink: /portfolio/bumi-mujoco/
date: 2026-07-18
header:
  teaser: projects/bumi-mujoco/1.jpg
gallery:
  - image_path: projects/bumi-mujoco/1.jpg
    url: projects/bumi-mujoco/1.jpg
    title: "Bumi in MuJoCo"
---

**Role:** Robotics software engineer · **Year:** 2026 · **Stack:** MuJoCo, DDS, C++, Python, noetix_sdk_bumi

**Code:** [bumi_mujoco](https://github.com/diaskabdualiev/bumi_mujoco)

## Overview

The equivalent of `unitree_mujoco` for the **Noetix Bumi** humanoid: the simulator speaks the same DDS topics as the real motion-control board, so any **noetix_sdk_bumi** client (low-level or high-level, C++ or Python) runs against simulation **without code changes**. Built while working on Bumi as a school assistant robot (lessons, voice, gestures).

## What I built

- **DDS bridge** that reproduces the robot's command and state topics in simulation.
- **MuJoCo model and scene** for Bumi, used to test controllers before running them on hardware.
- Documentation in English and Russian.

## Demo

{% if page.video_url or page.video_file %}{% include video.html %}{% else %}*🎥 Video demo coming soon.*{% endif %}

## Gallery

{% if page.gallery %}{% include gallery caption="Noetix Bumi in MuJoCo." %}{% else %}*📸 Screenshots coming soon.*{% endif %}
