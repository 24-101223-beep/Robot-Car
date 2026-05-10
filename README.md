# Arduino 4WD Smart Car

An intelligent Arduino-controlled 4-wheel drive robot car
with three autonomous and manual control modes, built as
a summer robotics course project.

## Modes
- **Obstacle Avoidance** — 4 ultrasonic sensors detect
  and autonomously navigate around obstacles in real-time
- **Line Tracking** — infrared sensor follows a predefined
  black line on the ground autonomously
- **Manual Control** — full remote control via Bluetooth
  using the Serial Bluetooth Terminal mobile app

## Hardware Components
- Arduino microcontroller
- 4 DC Motors + L298N Motor Driver
- 4 HC-SR04 Ultrasonic Sensors (360° coverage)
- 1 Infrared Line Tracker Sensor
- 1 Bluetooth Module
- Buck Converter (11.1V → 5V)
- 3 x 3.7V Li-ion Batteries in series
- 3D printed custom parts

## Software Logic
- Obstacle avoidance always takes priority
- Bluetooth manual override overrides all autonomous modes
- PWM signals control individual motor speed and direction
- PID control for smooth motor synchronization

## Technologies
- Arduino (C/C++)
- Embedded Systems
- Bluetooth Communication
- 3D Printing
- Sensor Fusion
