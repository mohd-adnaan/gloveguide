# 🧤 Glove Guide

**Glove Guide** is a wearable navigation system for cyclists, runners, and pedestrians that uses vibration feedback to provide turn-by-turn directions — no screens or sounds required. By integrating small motors into gloves and connecting them via Bluetooth to a mobile app using Google Maps API, users can focus on the road while navigating safely.

## Overview

- Reduces distraction from checking phones.
- Provides intuitive left/right vibration cues.
- Maintains full environmental awareness (no earphones or screens).
- Ideal for cyclists, runners, and visually impaired users.

## System design

**Hardware:** Gloves, ESP32, vibration actuators, battery, driver circuit.

**Software:**

- Mobile app → gets directions from Google Maps API.
- Bluetooth → sends turn instructions to ESP32.
- ESP32 firmware → activates the correct glove motor.

## Workflow

1. Set route in the Glove Guide mobile app.
2. Directions sent via Bluetooth to ESP32.
3. Left/right glove vibrates for turns.
4. User navigates safely, hands- and eyes-free.

## Ethics summary

- **Participants:** 5–10 cyclists (ages 17–70).
- **Risks:** Same as regular cycling.
- **Mitigation:** Only experienced riders participate.

## Detailed Documentation

For detailed information about our observations, research, and proposal, please check our comprehensive report:
[Observations and Proposal Document](https://drive.google.com/file/d/1vhEsAlTU161bzLwdcQ8EdqqY2YrobZBX/view?usp=sharing)

## Images

The images below are included from the `images/` folder to illustrate the user scenario and system architecture. They use relative paths so they'll render on GitHub and local previews.

![Person riding a bike — test ride scenario](images/man-on-bike.jpg)

*Figure 1 — Test ride / user scenario.*

![System architecture diagram](images/system-architecture.jpg)

*Figure 2 — System architecture overview (ESP32, mobile app, Bluetooth, actuators).* 

## 👥 Team

**Group G:** Kevin Wu, Mohammad Adnaan, William Goyens

**Institution:** McGill University — ECSE Design Project (Fall 2025)

