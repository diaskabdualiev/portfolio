---
title: "Physical AI Championship 2026 (2nd place) — Unitree G1 Pick-and-Deliver"
excerpt: "2nd place at Physical AI Championship 2026. Full-task pipeline on a Unitree G1 humanoid: autonomous walking, object search, grasping, return, and handover — focused on integrating perception, control, and behavior logic for a real robot."
collection: portfolio
permalink: /portfolio/unitree-g1-pick-and-deliver/
date: 2026-03-01

video_file: projects/unitree-g1-pick-and-deliver/demo.mp4
# header:
#   teaser: projects/unitree-g1-pick-and-deliver/cover.jpg
# video_url: https://www.youtube.com/embed/VIDEO_ID
# gallery:
#   - image_path: projects/unitree-g1-pick-and-deliver/1.jpg
#     url: projects/unitree-g1-pick-and-deliver/1.jpg
#     title: "Grasping the box"
#   - image_path: projects/unitree-g1-pick-and-deliver/2.jpg
#     url: projects/unitree-g1-pick-and-deliver/2.jpg
#     title: "Object handover"
header:
  teaser: projects/unitree-g1-pick-and-deliver/2.jpg
gallery:
  - image_path: projects/unitree-g1-pick-and-deliver/1.jpg
    url: projects/unitree-g1-pick-and-deliver/1.jpg
    title: "Competition scene in MuJoCo"
  - image_path: projects/unitree-g1-pick-and-deliver/2.jpg
    url: projects/unitree-g1-pick-and-deliver/2.jpg
    title: "Final run at Physical AI Championship 2026"
---

**Role:** Robotics software engineer · **Year:** 2026 · **Platform:** Unitree G1

**Result:** 🥈 **2nd place, Physical AI Championship 2026** (Unitree G1 track).

**Final run:** [YouTube](https://www.youtube.com/watch?v=g921UqeuDs4) · **Demo:** [YouTube Short](https://www.youtube.com/shorts/ItpIVivOTbk) · **Code:** [physical_ai_championship](https://github.com/diaskabdualiev/physical_ai_championship)

## Overview

A complete **task pipeline** on a **Unitree G1 humanoid robot**, executing the full cycle end to end: autonomous walking, searching for a box, grasping it, returning, and handing the object over. The emphasis was on tying **perception, control, and behavior logic** together into one reliable flow on a real robot.

## What I built

- Implemented the **full task cycle**: autonomous walking → object (box) search → grasp → return → handover.
- Integrated **perception** (locating and positioning relative to the target) with **motion and grasp control**.
- Built the **behavior logic** that sequences and coordinates each stage of the task.
- Focused on **real-robot integration** — making the perception/control/behavior stack work together on hardware.

## Demo

{% if page.video_url or page.video_file %}{% include video.html %}{% else %}*🎥 Video demo coming soon.*{% endif %}

## Gallery

{% if page.gallery %}{% include gallery caption="Autonomous pick-and-deliver task on the Unitree G1." %}{% else %}*📸 Screenshots coming soon.*{% endif %}
