# Smart Disaster Rescue & GPS Tracking System

An Arduino-based emergency rescue system. At the press of a button, it reads the user's live GPS location and sends it by SMS to a rescue team, while a buzzer and LED alert people nearby.

> CSE 382 — Introduction to Embedded Systems Lab, Section 11, Group 6, Spring 2026, Southeast University.
> Status: project proposal (design stage). Full proposal: [Smart_Disaster_Rescue_Proposal.pdf](Smart_Disaster_Rescue_Proposal.pdf)

## How It Works

1. The user presses the emergency push button.
2. The Arduino Uno reads the current position from the NEO-6M GPS module.
3. The SIM800L GSM module sends an SMS with the location (Google Maps link) to the rescue team.
4. The buzzer sounds and the LED lights up as a local alert.

## Components

| Component | Purpose |
|---|---|
| Arduino Uno | Main controller |
| NEO-6M GPS Module | Live location (latitude / longitude) |
| SIM800L GSM Module | SMS alert to the rescue team |
| Push Button | Emergency trigger |
| Buzzer | Audible alert |
| LED Indicator | Visual alert |
| Battery / Power Supply | Portable power |

## Team

- Fouzia Hoque (2023100000579)
- Md Emon Rana (2023100000645)
- MD Abir Hossen (2023100000423)

Department of Computer Science and Engineering, Southeast University.
