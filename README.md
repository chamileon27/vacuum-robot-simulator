# Vacuum robot simulator

**WORK IN PROGRESS**

A simulation environment for an autonomous robot that should (eventually) be
able to localize itself within and navigate through its (virtual) environment.

## Assumptions

- Two-dimensional world
- Static environment
- **Sensor:** 360° laser scanner - with simulated measurement noise
- **Control:** rotate_by(*angle*), drive_forward(*distance*) - with simulated imprecision

## Software architecture (planned)
<img src="architecture.svg" alt="Software architecture" width="100%">

## Preview
![Preview](https://i.imgur.com/lXAIxby.png)
