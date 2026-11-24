---
title: "Unitree Go2 — RL Locomotion in MuJoCo, Running in the Browser"
excerpt: "Velocity-tracking walking policy for the Unitree Go2 quadruped, trained from scratch with PPO and deployed in a browser app: MuJoCo WASM physics plus an ONNX policy loop."
collection: portfolio
permalink: /portfolio/unitree-go2-rl-mujoco/
date: 2026-05-10
video_url: https://www.youtube.com/embed/smxh8Uu2Zpo
header:
  teaser: projects/unitree-go2-rl-mujoco/1.jpg
gallery:
  - image_path: projects/unitree-go2-rl-mujoco/1.jpg
    url: projects/unitree-go2-rl-mujoco/1.jpg
    title: "Go2 policy in MuJoCo"
---

**Role:** Robotics software engineer · **Year:** 2026 · **Stack:** MuJoCo, mjlab, PPO, ONNX, MuJoCo WASM, React, TypeScript

**Live demo:** [diaskabdualiev.github.io/go2-web-mujoco](https://diaskabdualiev.github.io/go2-web-mujoco/) · **Code:** [go2-web-mujoco](https://github.com/diaskabdualiev/go2-web-mujoco)

## Overview

A walking policy for the **Unitree Go2 quadruped**, trained from scratch in MuJoCo with **PPO** (about 18 minutes on 10 GPUs, see the video), then exported to **ONNX** and run in an editable browser app on top of **MuJoCo compiled to WebAssembly**.

## What I built

- Trained a **velocity-tracking locomotion policy** for the Go2 in simulation.
- Exported the policy to **ONNX** and wrote the inference loop that drives the simulated robot in real time.
- Built a **browser app** (React, TypeScript, MuJoCo WASM) with controls, so the policy can be tried without installing anything.

## Demo

{% if page.video_url or page.video_file %}{% include video.html %}{% else %}*🎥 Video demo coming soon.*{% endif %}

## Gallery

{% if page.gallery %}{% include gallery caption="Unitree Go2 policy in MuJoCo." %}{% else %}*📸 Screenshots coming soon.*{% endif %}
