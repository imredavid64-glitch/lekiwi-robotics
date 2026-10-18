# LeKiwi Omnidirectional Robot

A custom-engineered **Kiwi-drive** mechatronic robot — a three-wheel omnidirectional (holonomic) platform capable of translating and rotating in any direction without changing wheel orientation.

---

## Why Kiwi drive

With three rollers arranged at 120°, the robot can strafe sideways, spin in place, and move along any vector — all at the same time. This makes it far more manoeuvrable than a differential-drive chassis in tight indoor spaces.

## Mechanical design

| Component | Detail |
|---|---|
| **Drive** | 3-wheel Kiwi / Mecanum-style omnidirectional |
| **Motors** | Independently driven, closed-loop speed control |
| **Chassis** | Custom fabricated frame with balanced weight distribution |
| **Sensors** | Ultrasonic distance sensors for obstacle avoidance |

## Control system

- **Microcontroller** — ESP32 / Arduino handling PWM motor control
- **Closed-loop sync** — encoder feedback keeps all three wheels synchronised so the robot doesn't drift
- **Vector kinematics** — movement commands are resolved into per-wheel velocities, so a single input can produce translation, rotation, or both simultaneously
- **Wireless telemetry** — live speed, distance, and sensor data streamed to a dashboard

## Features

- 3-wheel Kiwi holonomic omnidirectional drive kinematics
- ESP32 / Arduino PWM motor control with closed-loop sync
- Ultrasonic distance sensing and live telemetry dashboard
- Vector translation and rotation from a single control input

## Links

- **Founder** — [@imredavid64-glitch](https://github.com/imredavid64-glitch)

---

*Part of the [DSIndieAI](https://dsindieai.vercel.app) robotics program.*
