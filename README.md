[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/N9fO8RHZ)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=22800482&assignment_repo_type=AssignmentRepo)
# Lab 01 – Manual VR Setup (URP) without VR Template

Unity Version: 2022.3 LTS  
Lab Duration: 2 Hours  

---

## Goal

Learn how to manually configure a Virtual Reality project in Unity using:

- 3D URP template
- OpenXR
- XR Interaction Toolkit

This project is not reused in later labs.

---

## Learning Outcomes

After completing this lab, you will be able to:

- Create a URP project in Unity
- Install XR packages using Package Manager
- Enable and configure OpenXR
- Add XR Origin (Action-based) manually
- Setup teleport locomotion using a floor surface
- Verify a basic VR scene setup

---

## Software Requirements

- Unity 2022.3 LTS
- Windows PC
- VR headset (optional)

---

## Task Instructions

1. Create a new project using: Template: 3D (URP) | Project Name: Lab01_ManualVR_URP

2. Install packages:

- XR Plug-in Management
- OpenXR Plugin
- XR Interaction Toolkit
- Input System

3. Enable OpenXR:
   
Edit → Project Settings → XR Plug-in Management → Enable OpenXR


4. Add XR Origin:

Hierarchy → XR → XR Origin (Action-based)


5. Create floor:

3D Object → Plane
Rename: Ground
Scale: (3,1,3)


6. Add Teleportation Area component to Ground.

7. Add objects:

- Cube
- Sphere
- Capsule

8. Enter Play Mode to verify setup.

---

## Submission

Record a 30–60 second screen video showing:

- XR Origin in Hierarchy
- Ground object with Teleportation Area
- Play Mode running

File name:

Lab01_<ITNo>.mp4


Upload the video file to this repository and push your changes.

---

## Notes

- This project is only for Lab 01.
- Lab 02 will start a new project using the VR Core Template.
- Use the same Unity version for all labs.

---


Labsheet Created by Nushkan Nismi
