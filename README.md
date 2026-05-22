# Project Airframe — Product Showcase

<img width="4000" height="3000" alt="render57" src="https://github.com/user-attachments/assets/d3f89bba-c040-440f-a4fb-2a46195fc61b" />

**Project Airframe** is my current smartwatch project. The idea is to build a premium smartwatch around a removable internal **Tech Puck**, so the watch body can stay the same while the electronics inside can be serviced, repaired, or upgraded.

This page is not meant to be a build guide or an open-source README. It is a visual overview of where the project is right now: product renders, prototype hardware, PCB work, app screens, and the main product idea.

The short version: **keep the watch, upgrade the technology inside it.**

---

## Product Idea

Most smartwatches are treated like short-life electronics. After a few years the battery gets worse, the sensors improve, the chip feels old, and the whole watch gets replaced.

Airframe takes a different approach. The outer watch is treated more like a real watch: something you keep, wear, repair, and build attachment to. The fast-moving parts sit inside a replaceable puck.

That means the product can be improved without throwing away the whole object.


<img width="3300" height="2000" alt="render48" src="https://github.com/user-attachments/assets/91b90df5-8541-42a8-9453-a18f4cacdd1c" />
<img width="1672" height="941" alt="ChatGPT Image 3  Mai 2026, 15_06_51" src="https://github.com/user-attachments/assets/d027cc96-c536-4028-ba48-e761e106296d" />

---

## What Airframe Is

Airframe is built around two main parts:

1. **The watch body**  
   The visible, long-term part of the product. This includes the case, strap system, materials, buttons, protection, and overall look of the watch.

2. **The Tech Puck**  
   The internal technology core. This holds the parts that age faster: display, processor, battery, sensors, wireless charging, connectivity, and security hardware.

The goal is simple: the user should not have to replace the whole watch just because one internal part gets old.

---

## Main Features

- Round smartwatch design with a premium watch-style direction
- Replaceable internal Tech Puck
- 240 × 240 px touch display
- Multiple watch-face layouts
- Companion app for settings, syncing, watch faces, and health views
- Heart rate, SpO₂, ECG-style graphing, temperature, sleep, and activity tracking direction
- Step counting, calories, IMU movement tracking, compass, pressure, and altitude support
- Bluetooth LE sync
- GPS/GNSS and NFC paths in the project
- Wireless charging direction
- Battery-management, protection, and fuel-gauge circuitry
- Privacy direction with a keep-data-on-device concept
- Security direction around signed updates and authenticated modules

Some of this is already reflected in the repo, firmware, app screens, BOMs, and prototype assets. Other parts are still product direction and need more development before they can be treated as final.

---

## Hardware Direction

The current hardware work points toward a round smartwatch with a layered internal electronics core.

The main implemented firmware path is based around the **ESP32-S3**. There is also an **NXP i.MX 8 Quad** circular-board direction in the project assets, but that is more of a secondary exploration at this stage.

Current hardware direction includes:

- ESP32-S3-centered watch firmware path
- 240 × 240 px circular touch display
- Battery charging, protection, and fuel-gauge circuitry
- Wireless charging direction
- ECG, pulse oximeter, temperature, pressure, IMU, and compass sensor paths
- Bluetooth LE, GPS/GNSS, and NFC hardware/software paths
- Prototype boards and integration photos showing the project beyond just renders

---

## Hardware Gallery

1. **Airframe smartwatch prototype**
<img width="4032" height="3024" alt="watch_prototype_3043" src="https://github.com/user-attachments/assets/5eff5249-41cf-4322-b472-47555cfccfb7" />

2. **Smartwatch components and PCB designs**  
<img width="4032" height="3024" alt="integration_prototype_2981" src="https://github.com/user-attachments/assets/5d0059d0-7703-4eb6-bd0e-3c8a18e6826f" />


3. **Assembled form — front and back**
<img width="5000" height="6000" alt="372151565-4cb15749-a03a-4ba1-91e2-6235cf5d4ce2" src="https://github.com/user-attachments/assets/9b456c1a-1031-4744-9428-d52d5f0c79a0" />

   
4. **Tech Puck direction**
<img width="1030" height="770" alt="372154330-f66506e5-2965-4dd6-ac76-fcacb692d002" src="https://github.com/user-attachments/assets/acc64775-70be-4929-a871-c5e1cdaf2f3d" />
<img width="1254" height="1254" alt="ChatGPT Image 3  Mai 2026, 18_41_12" src="https://github.com/user-attachments/assets/e31c0b89-b2a2-4b47-bad9-910a2bdab3ab" />


---

## Tech Puck

The Tech Puck is the main product idea behind Airframe.

It is a compact round module that sits inside the watch body. Instead of making the whole smartwatch one sealed disposable unit, the parts that change fastest are grouped into a serviceable internal core.

The puck can include:

| Layer | What it handles |
|---|---|
| Display | Touch display, cover interface, panel, brightness, visual quality |
| Compute | Processor, memory, connectivity, OS performance, local processing |
| Battery | Cell, charging behavior, power management, battery health |
| Sensors | Health, motion, environmental, and fitness sensors |
| Charging / interface | Wireless charging coil, service contacts, NFC-related parts |
| Security | Secure element, module authentication, encrypted key storage |

The important part is that this should not feel like a DIY module or fragile experiment. The watch still has to feel sealed, premium, and reliable. Serviceability should make the product better, not make it feel less finished.

---

## Software Experience

Airframe also has a companion app direction. The app is used for setup, Bluetooth sync, watch-face selection, settings, and health/activity views.

Current software direction includes:

- Bluetooth LE sync between the watch and phone
- Watch-face selection
- Health dashboards for heart rate, SpO₂, ECG-style data, temperature, sleep, and activity
- Device settings for Bluetooth, NFC, GPS, software updates, messages, ECG, compass, and related features
- Daily stats such as steps, calories, altitude, sleep history, and activity summaries
- Privacy settings, including a direction for keeping sensitive data on-device

### Software Images

1. **Airframe mobile app dashboard**  
<img width="5000" height="3000" alt="372151895-7a61117e-b7ba-4130-8972-cf81db6b3340" src="https://github.com/user-attachments/assets/3ca3b299-57d9-40e7-a2d5-f47575c1ca1f" />


2. **Frame-OS / watch software direction**  
<img width="821" height="481" alt="372154881-5502f927-6beb-450d-83aa-34725e6c004d-2" src="https://github.com/user-attachments/assets/a27f09c7-47ea-4546-8f40-a77b8c5e8016" />

---

## PCB & Electronics

The electronics side of the project includes PCB work, BOMs, sensor paths, power-management parts, wireless features, and prototype board images.

The current electronics direction includes:

- ESP32-S3 watch firmware path
- Secondary NXP i.MX 8 exploration
- ECG, SpO₂, IMU, compass, temperature, pressure, and altitude-related sensing
- Battery charger, battery protection, and fuel-gauge circuitry
- NFC and GPS/GNSS paths
- Wireless charging direction
- PCB and prototype board work that supports the product direction

### PCB Design

1. **PCB**
<img width="3000" height="6000" alt="render52" src="https://github.com/user-attachments/assets/71d8173f-0fce-48ee-a62e-86f329025b68" />
<img width="1254" height="1254" alt="ChatGPT Image 3  Mai 2026, 15_25_02" src="https://github.com/user-attachments/assets/0cb00d73-3b29-4312-83c2-5a895e70defc" />


---

## Ownership and Security

The product is not only about swapping hardware. If the watch collects health, sleep, movement, location, and identity-related data, the user also needs control over that data.

That means Airframe needs a security and ownership model from the start.

The direction is:

- Make it clear what stays on the device and what syncs
- Encrypt sensitive health and personal data
- Use signed firmware and software updates
- Authenticate replaceable modules so the watch can detect genuine and compatible parts
- Allow service and diagnostics without exposing private user data
- Keep research or experimental algorithms away from production data until they are properly tested

Security should be something the user can understand, not just something hidden in the background.

---

## Product Direction

The current product direction is built around a few core points:

- **Keep the watch longer** instead of replacing it every few years
- **Upgrade the puck** when technology improves
- **Replace the battery** without making the whole watch obsolete
- **Treat the body like a premium object** that is worth maintaining
- **Protect user data** as part of the ownership promise
- **Use service and upgrades** as part of the product lifecycle
- **Leave room for research partnerships** around health, sensors, AI, and battery optimization

The long-term idea is a smartwatch that feels less like a disposable gadget and more like a watch you actually want to keep.

---

## Current Project Gallery

These images show the current Airframe direction: PCB work, prototype assemblies, app concepts, puck designs, and watch renders.

<img width="1254" height="1254" alt="ChatGPT Image 3  Mai 2026, 15_25_02" src="https://github.com/user-attachments/assets/ef806b9b-368f-4967-a954-f2e2f85b1ad8" />
<img width="1000" height="1000" alt="render62" src="https://github.com/user-attachments/assets/40a83e53-1ccc-4371-985c-e57543625d3d" />
<img width="4032" height="3024" alt="board_prototype_2922" src="https://github.com/user-attachments/assets/960b0ee9-b402-4263-82b7-059c36c2b6a3" />
<img width="3024" height="4032" alt="watch_prototype_3025" src="https://github.com/user-attachments/assets/c6902741-2d32-4c2d-aa39-0bb9ff3a94c4" />
<img width="2221" height="2304" alt="Render46 1" src="https://github.com/user-attachments/assets/fd53dc34-d73a-4668-a993-fa621adfe910" />
<img width="1672" height="941" alt="ChatGPT Image 3  Mai 2026, 18_39_03" src="https://github.com/user-attachments/assets/546b640b-6635-4654-a929-d0f8b0dd06c2" />



---

## Summary

Airframe is a smartwatch project built around a premium body and a replaceable Tech Puck.

The current project already shows the main direction: round watch design, prototype hardware, PCB work, app screens, health/activity features, wireless paths, and a serviceable internal architecture.

The goal is to make a smartwatch that does not have to be thrown away when the technology inside gets old.
