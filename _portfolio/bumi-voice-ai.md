---
title: "Bumi Voice AI — Voice Assistant and Voice-to-Motion for a Humanoid"
excerpt: "Voice assistant for the Noetix Bumi humanoid on NVIDIA Jetson: live dialogue through Gemini Live API, function calling mapped to safe robot motions over DDS, and a web dashboard."
collection: portfolio
permalink: /portfolio/bumi-voice-ai/
date: 2026-08-19
video_file: projects/bumi-voice-ai/demo.mp4
---

**Role:** Robotics software engineer · **Year:** 2026 · **Stack:** Gemini Live API, Python, FastAPI, Next.js, Docker, CycloneDDS, Noetix SDK, NVIDIA Jetson

## Overview

A voice assistant that turns the **Noetix Bumi** humanoid from a remote-controlled device into a companion that talks and moves. The robot hears speech, holds a live conversation through **Gemini Live API**, and triggers physical actions through the robot's native SDK. Deployed on two robots.

## What I built

- **Voice agent** on Gemini Live API: streaming dialogue with interruption support, retries, and configurable model, voice and prompt.
- **Voice to motion, safely:** model function calls go through a backend endpoint with an action whitelist, a robot-mode guard and a busy lock, then reach the motion board over **DDS**.
- **Web dashboard** (Next.js + FastAPI): system status, real battery level and robot mode from the SDK, command buttons, dialogue logs, AI settings.
- **Robust deployment** on the Jetson with Docker Compose: SDK start-up under a timeout with fallback to a mock controller, DDS network setup, and a deploy script with selective rebuilds.

## Demo

<div style="max-width:360px;margin:1.5em auto;"><video controls playsinline style="width:100%;border-radius:6px;background:#000;"><source src="{{ site.baseurl }}/images/projects/bumi-voice-ai/demo.mp4" type="video/mp4"></video></div>
