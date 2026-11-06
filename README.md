# Remote-Controlled Robo Racer

A 4-wheel remote-controlled robot racer built with 12V 775 DC motors, Hobbywing QuicRun 1060 brushed ESCs and a FlySky 2.4 GHz transmitter and receiver.

## Overview
The robot is driven wirelessly from a FlySky FS-i6X transmitter. The receiver on the robot passes the control signals to the brushed electronic speed controllers (ESCs), which drive the DC motors to control speed and direction.

## Components
| Component | Purpose |
|---|---|
| FlySky FS-i6X transmitter (2.4 GHz, AFHDS 2A) | Wireless remote control |
| FlySky receiver with antenna | Receives control signals on the robot |
| Hobbywing QuicRun 1060 brushed ESC | Controls the speed and direction of the DC motors |
| 775 DC motors (12V) | Drive the wheels |
| LiPo battery (12V) | Power supply |
| 4 off-road wheels and a custom chassis | Mechanical base |

## How it works
1. The operator moves the sticks on the FlySky transmitter.
2. The receiver picks up the 2.4 GHz signal through its antenna.
3. The receiver sends control signals to the brushed ESCs.
4. The ESCs regulate the power from the LiPo battery to the 775 DC motors, controlling speed and steering.

## Team
[fill in: names, or "Individual project"]

## Files in this repository
- `images/` photos of the robot
- `demo/` demo video (if available)
