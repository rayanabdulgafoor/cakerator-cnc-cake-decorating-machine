# Cakerator: Polar Configuration Cake Decorating Robot

3-DOF polar robotic cake decorating system designed for precise rotational and radial motion control.

![Hero Image](/assets/hero_shot.jpg)

[Presentation Video](https://www.youtube.com/watch?v=__ybdY_pd08)

---

## Full Project Documentation

Detailed project documentation, fabrication workflows, firmware architecture, and testing results are available here:

[Portfolio Documentation](https://www.rayanabdulgafoor.in/projects/machines/cakerator/index.html)

---

## Overview

Cakerator is a 3-DOF polar configuration robotic system developed for automated cake decoration applications. The system combines coordinated multi-axis motion control, embedded firmware integration, and precision mechanical transmission to enable repeatable 360° decoration workflows.

The robot was engineered using a polar kinematic architecture consisting of rotational, radial, and extrusion axes driven by synchronized stepper motor control. The project focused on precision motion, repeatability, homing calibration, and compact electromechanical integration.

---

## Key Features

* 3-DOF polar robotic architecture
* High-precision rotational cake decorating system
* 8:1 gear-reduced turntable with 0.225° angular resolution
* Coordinated multi-axis motion control
* ESP32 + GRBL motion control implementation
* Inductive homing and calibration system
* Repeatable rotational and linear positioning
* Embedded stepper motor control using DRV8825 drivers

---

## Tech Stack / Hardware

ESP32 | GRBL | NEMA17 Stepper Motors | DRV8825 Drivers | Inductive Sensors | Fusion 360 | Embedded Systems | Arduino IDE

---

## System Architecture

The robotic system consists of three coordinated motion axes:

* Rotational Axis (Turntable)
* Radial Linear Axis
* Extrusion Axis

Motion control was implemented using ESP32-based GRBL firmware to coordinate synchronized movement across all axes for controlled decoration trajectories.

---

## Mechanical Design Highlights

* Polar robot configuration optimized for rotational workflows
* 8:1 gear-reduced turntable for higher positioning precision
* Compact multi-axis mechanical integration
* Custom transmission and mounting architecture
* Modular subsystem design for easier calibration and maintenance

---

## Embedded & Motion Control System

* ESP32-based motion control architecture
* GRBL firmware implementation for coordinated motion control
* DRV8825 stepper motor driver integration
* Multi-axis synchronization and trajectory execution
* Inductive homing and calibration workflows
* Repeatable position control across rotational and linear axes

---

## License

This project is licensed under the MIT License.
