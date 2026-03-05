# Manolo Garabini's Team Repos Guide

## General Guides

- [`mulinex_guide`](https://github.com/CentroEPiaggio/mulinex_guide): General guides to setup and use the family of Mulinex robots.

## Robot Descriptions

- [`mulinex_description`](https://github.com/CentroEPiaggio/mulinex_description): URDF description of Mulinex robots (Otto, OmniQuad, OmniGoat, OmniCar).

## Hardware & Low-Level ROS 2 Controller

- [`Docker NUC Mulinex`](https://github.com/CentroEPiaggio/docker_nuc_mulinex): Docker configuration for the NUC of the Mulinex project.
- [`Mulinex SBC Workspace`](https://github.com/CentroEPiaggio/mulsbc_ws): ROS 2 workspace for the Mulinex SBC (Raspberry) with the hardware interface and low-level controllers.
- [`Pi3Hat Controllers`](https://github.com/CentroEPiaggio/pi3hat_controllers): TODO. --- (May be removed in the future as Mulinex SBC Workspace has it (not as a submodule).)
- [`Pi3Hat Robotic Systems`](https://github.com/CentroEPiaggio/pi3hat_robotic_systems): Low level Pi3Hat interfaces for the mulinex project. --- (May be removed in the future as Mulinex SBC Workspace has it (not as a submodule).)

## Various Controllers

- [`Omni Mulinex Joystick`](https://github.com/CentroEPiaggio/omni_mulinex_joystick): Joystick controller for teleoperating Mulinex robots. --- (May be removed in the future as Mulinex SBC Workspace has it (not as a submodule).)

## High-Level Control

<details>
<summary> Model-Based Control - click to expand</summary>

### Model-Based Control

#### Davide De Benedittis

- [`Control Arm Temperature`](https://github.com/CentroEPiaggio/control_arm_temperature): temperature aware control of robotic arms
- [`Control Quadrupeds Soft Contacts`](https://github.com/CentroEPiaggio/control_quadrupeds_soft_contacts): quadruped control that considers soft contacts with the environment.

</details>

<details>
<summary> Learning-Based Control - click to expand</summary>

### Learning-Based Control

#### Simone Tolomei et al.

- [`Isaac Centro Piaggio Suite`](https://github.com/CentroEPiaggio/isaac_centropiaggio_suite): Isaac Lab extension for RL. **WIP**. Will include pick and throw, perceptive manipulation, locomotion (Otto, OmniQuad, TrackQuad), and more.

</details>

## Utilities

<details>
<summary> Various utilities - click to expand</summary>

- [`IKEA Interface`](https://github.com/CentroEPiaggio/IKEA_interface): tool that automatically searches, downloads, and processes 3D assets from the IKEA dataset into URDF format.

</details>