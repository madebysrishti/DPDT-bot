# DPDT Controlled Dual-Purpose Wired Robot

## Overview
A high-torque, wired mobile robot designed for both robotic soccer and obstacle race competitions. The robot uses manual DPDT switch-based control and four 12V Johnson geared motors to deliver strong torque, stability, and directional precision.

Unlike microcontroller-based systems, this robot focuses on robust electromechanical design and direct hardware control.

---

## Design Objective
- Build a powerful wired robot capable of handling impact (soccer) and hurdles (race).
- Ensure high torque output using geared Johnson motors.
- Implement reliable manual directional control using DPDT switching.
- Maintain structural stability under load.

---

## Hardware Components

- 4 × 12V Johnson Geared Motors
- 2 × DPDT (Double Pole Double Throw) Switches
- 12V Power Supply / Battery
- Heavy-duty Chassis
- Wheels
- Wiring & Connectors

---

## Working Principle

Each DPDT switch controls the polarity supplied to a pair of motors.

By reversing polarity through DPDT switching:
- Motor direction is reversed.
- The robot can move forward or backward.

With two DPDT switches:
- One controls left-side motors.
- One controls right-side motors.

### Movement Logic

- Both switches forward → Move Forward
- Both switches reversed → Move Backward
- Left forward + Right reverse → Turn Right
- Left reverse + Right forward → Turn Left

This creates a simple yet effective differential drive system.

---

## Key Concepts Applied

- Polarity Reversal using DPDT Switching
- High-Torque Motor Drive Systems
- Differential Drive Mechanics
- Load Handling & Stability Design
- Power Distribution in 12V Systems
- Practical Wiring & Hardware Debugging

---

## Mechanical Advantages

- High torque output for pushing force (soccer).
- Stable 4-motor configuration for better traction.
- Simple and robust control system.
- No software dependency — low failure risk.

---

## Challenges Faced

- Managing current draw from four motors.
- Ensuring stable wiring connections.
- Heat management under continuous load.
- Maintaining balance during impact.

---

## Learning Outcomes

- Deep understanding of motor polarity control.
- Practical experience with DPDT switching.
- High-current power handling.
- Real-world mechanical stress testing.
- Hardware-only control system design.

---

## Future Improvements

- Add motor driver + microcontroller integration.
- Implement wireless control.
- Add speed control using PWM.
- Add sensor-based automation.
