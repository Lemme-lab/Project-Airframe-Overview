# Project Airframe — Product Showcase

![244198878-646c22c4-e374-44d6-ac0f-87877a9a3229 (1)](https://github.com/user-attachments/assets/7a5e7fc0-9f43-4ed2-866d-ce484d9eea08)

**Project Airframe** is my current smartwatch project. The idea is to build a premium smartwatch around a removable internal **Tech Puck**, so the watch body can stay the same while the electronics inside can be serviced, repaired, or upgraded.

This page is not meant to be a build guide or an open-source README. It is a visual overview of where the project is right now: product renders, prototype hardware, PCB work, app screens, and the main product idea.

The short version: **keep the watch, upgrade the technology inside it.**

---

## Product Idea

Most smartwatches are treated like short-life electronics. After a few years the battery gets worse, the sensors improve, the chip feels old, and the whole watch gets replaced.

Airframe takes a different approach. The outer watch is treated more like a real watch: something you keep, wear, repair, and build attachment to. The fast-moving parts sit inside a replaceable puck.

That means the product can be improved without throwing away the whole object.

![241293606-e9c87f54-92d8-475b-8504-8d2cf418f53a](https://github.com/user-attachments/assets/693da952-6e1c-453d-a6ec-a126f1c2ab03)
![207326701-55a5ec6b-7f79-4fc3-8bfd-e77caa1cd0b9](https://github.com/user-attachments/assets/4d40084b-7ca1-4a87-8b07-80a2468a00cc)

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
   ![248464943-83f1d933-ee97-4bca-aef9-81b796344c9b](https://github.com/user-attachments/assets/3a7f311c-2e9c-446f-94e9-5d0d884ee9e1)

2. **Smartwatch components and PCB designs**  
   ![248467414-c0ff1934-5fe4-4696-9213-ace8d471f633 (1)](https://github.com/user-attachments/assets/4cb15749-a03a-4ba1-91e2-6235cf5d4ce2)

3. **Assembled form — front and back**
   ![248465391-174d9c86-a782-402c-9f40-d455ebd8f1ef](https://github.com/user-attachments/assets/88d6a27c-0659-45d0-a401-6666e3d667b4)
   
4. **Tech Puck direction**
   ![Screenshot 2024-09-30 174631](https://github.com/user-attachments/assets/f66506e5-2965-4dd6-ac76-fcacb692d002)
   ![211921454-efc67dd0-3a86-407a-a53b-dbce7d059ead](https://github.com/user-attachments/assets/1e383d4d-ad63-4f46-b15b-b5678c955e0d)

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
![227036885-2fcf2675-f2de-432f-a74a-1f8b804b1e94](https://github.com/user-attachments/assets/7a61117e-b7ba-4130-8972-cf81db6b3340)

2. **Frame-OS / watch software direction**  
![Screenshot 2024-09-30 175040](https://github.com/user-attachments/assets/5502f927-6beb-450d-83aa-34725e6c004d)

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
   ![241123783-0ecd49ee-87ff-4cde-9060-24d48c5cfade](https://github.com/user-attachments/assets/2314dfe0-84d8-4635-9061-3e2ef1ed1341)

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
![227036885-2fcf2675-f2de-432f-a74a-1f8b804b1e94](https://github.com/user-attachments/assets/dc71fa96-021d-498c-95cd-1b7353347f7b)
![211921454-efc67dd0-3a86-407a-a53b-dbce7d059ead](https://github.com/user-attachments/assets/d7088ce9-c997-458a-9e91-dc985a632ba4)
![248467414-c0ff1934-5fe4-4696-9213-ace8d471f633 (1)](https://github.com/user-attachments/assets/61887194-b57b-45d6-9b67-0e76043d813e)
![248465391-174d9c86-a782-402c-9f40-d455ebd8f1ef](https://github.com/user-attachments/assets/6e123352-491e-40b5-af0f-9c0008e83fb9)
![248465139-50e438e8-4756-424c-868c-67f0bfdfedbb](https://github.com/user-attachments/assets/a68f6fce-e5cd-4bab-bd28-738f808581b7)
![248464943-83f1d933-ee97-4bca-aef9-81b796344c9b](https://github.com/user-attachments/assets/a76052a9-a93f-41f6-9087-b57bb3987414)
![244199015-1c1b4e0c-4dde-461f-a7b2-ccfb9a86e202](https://github.com/user-attachments/assets/92ec8bbe-2105-4832-90a0-8a6831f65365)
![244198923-7aafcdc3-8758-4472-8234-4ef7c5881dfe](https://github.com/user-attachments/assets/8199f988-7c31-4913-b2d4-b22e3f266962)
![241293606-e9c87f54-92d8-475b-8504-8d2cf418f53a](https://github.com/user-attachments/assets/979d5030-795e-4fb5-97d5-64fe775a2b9d)
![248467414-c0ff1934-5fe4-4696-9213-ace8d471f633](https://github.com/user-attachments/assets/172599c9-fc08-4d54-b06c-b6f6def764fe)

---

## Summary

Airframe is a smartwatch project built around a premium body and a replaceable Tech Puck.

The current project already shows the main direction: round watch design, prototype hardware, PCB work, app screens, health/activity features, wireless paths, and a serviceable internal architecture.

The goal is to make a smartwatch that does not have to be thrown away when the technology inside gets old.
