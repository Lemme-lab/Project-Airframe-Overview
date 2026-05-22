# Project Airframe

![244198878-646c22c4-e374-44d6-ac0f-87877a9a3229 (1)](https://github.com/user-attachments/assets/7a5e7fc0-9f43-4ed2-866d-ce484d9eea08)

**Status:** Airframe is currently best understood as an R&D and portfolio repository. It is not packaged as a finished end-to-end build, and I would not recommend treating it as a ready-to-build DIY smartwatch kit yet. Contributions are still welcome, especially around documentation, cleanup, and focused subsystem work.

**Airframe** is a long-running smartwatch project built around a different ownership model: keep the watch body, replace or upgrade the parts that age fastest. The repo brings together product thinking, hardware exploration, embedded experiments, companion app work, renders, and presentation assets for that broader goal.

## Table of Contents
1. [Overview](#overview)
2. [Product Direction](#product-direction)
3. [What This Repo Contains](#what-this-repo-contains)
4. [Hardware Snapshot](#hardware-snapshot)
5. [Software Snapshot](#software-snapshot)
6. [Current State](#current-state)
7. [Contributing](#contributing)
8. [Gallery](#gallery)
9. [License](#license)

## Overview

Airframe is no longer framed here as "an open-source smartwatch you can build today." The more accurate description is a cross-disciplinary wearable project exploring a premium round watch, custom software, and a serviceable internal tech puck that can be repaired, replaced, or upgraded without discarding the whole object.

The repo matters because it shows the project across multiple layers at once:

- product direction and ownership model
- hardware and electronics exploration
- embedded and firmware experiments
- companion software and interface work
- visual development, storytelling, and launch thinking

## Product Direction

The current goals are centered on a durable smartwatch product rather than a generic dev board on the wrist:

- **Serviceable Core**: The internal tech puck is intended to be the replaceable part, so the watch can last longer as batteries, radios, and compute platforms change.
- **Premium Watch Object**: The outer watch should feel like something worth keeping, not disposable consumer electronics.
- **Owner-Controlled Software**: Airframe explores a custom software stack across the watch and companion experience instead of depending entirely on a closed platform.
- **Everyday Utility**: Health, activity, location, notifications, charging, and core watch functions remain the practical baseline.
- **Longer Product Life**: The bigger idea is longevity, upgradeability, and better ownership rather than yearly replacement.

## What This Repo Contains

| Area | Purpose |
| --- | --- |
| [`Code/`](./Code/) | Embedded, mobile, and supporting code experiments |
| [`Hardware/`](./Hardware/) | Hardware working files and related assets |
| [`Images/`](./Images/) | Renders, visual exploration, and prototype imagery |
| [`landing/`](./landing/) | Product-facing landing page and presentation layer |
| [`github-showcase/`](./github-showcase/) | Sanitized portfolio snapshot of the project |
| [`Reports/`](./Reports/) | Supporting written material and structured outputs |

## Hardware Snapshot

Airframe has explored multiple hardware directions rather than a single locked production architecture. Across those iterations, the watch concept has included:

- **Round Touch Display**: 240 x 240 watch interface target
- **Wireless Charging**: charging puck and battery-management exploration
- **Connectivity**: BLE, Wi-Fi, NFC, and GPS/GNSS concepts
- **Sensors**: ECG, pulse oximetry, temperature, pressure, IMU, compass, and related health/fitness inputs
- **Compute Paths**: experiments around both ESP32-S3 and higher-end processor options

The important point is not that every part is finished in one unified stack today, but that the repo documents the breadth of the hardware direction and the product logic behind it.

![241293606-e9c87f54-92d8-475b-8504-8d2cf418f53a](https://github.com/user-attachments/assets/693da952-6e1c-453d-a6ec-a126f1c2ab03)
![207326701-55a5ec6b-7f79-4fc3-8bfd-e77caa1cd0b9](https://github.com/user-attachments/assets/4d40084b-7ca1-4a87-8b07-80a2468a00cc)

## Software Snapshot

The software side of Airframe spans more than firmware alone. The project includes:

- **On-Watch UI Concepts**: interface exploration for a round smartwatch display
- **Companion App Work**: Flutter-based mobile app experiments
- **BLE Communication**: watch-to-phone/device connectivity work
- **Health and Activity Flows**: dashboards and interaction concepts for wearable data
- **Product Presentation**: a polished landing experience that explains the product idea clearly

Runnable pieces live in their own folders. If you want to explore the software directly, start with:

- [`landing/README.md`](./landing/README.md)
- [`Code/airframe_smartwatch_app/README.md`](./Code/airframe_smartwatch_app/README.md)

### Software Images

1. **Airframe Mobile App - Dashboard View**  
![227036885-2fcf2675-f2de-432f-a74a-1f8b804b1e94](https://github.com/user-attachments/assets/7a61117e-b7ba-4130-8972-cf81db6b3340)

2. **Frame OS Concept**  
![Screenshot 2024-09-30 175040](https://github.com/user-attachments/assets/5502f927-6beb-450d-83aa-34725e6c004d)

## Current State

This repository is a mix of prototype work, concept material, implementation experiments, and presentation assets. A few practical notes:

- the full system is not integrated into a polished production stack
- some directions were explored in parallel and are incomplete
- the repo is useful today as reference material, design/engineering evidence, and a base for focused follow-on work
- the landing page and showcase reflect the current product framing better than the old build-guide README did

## Contributing

Contributions are welcome, especially if they move the repo toward more clarity or better subsystem quality. Useful areas include:

- documentation cleanup
- repo organization
- firmware or app cleanup
- hardware annotation and component mapping
- focused experiments that support the serviceable-watch direction

If you want to contribute, open an issue or send a pull request with a narrowly scoped change.

## Gallery

1. **Airframe Smartwatch Prototype**
   ![248464943-83f1d933-ee97-4bca-aef9-81b796344c9b](https://github.com/user-attachments/assets/3a7f311c-2e9c-446f-94e9-5d0d884ee9e1)

2. **Components and PCB Design**
   ![248467414-c0ff1934-5fe4-4696-9213-ace8d471f633 (1)](https://github.com/user-attachments/assets/4cb15749-a03a-4ba1-91e2-6235cf5d4ce2)

3. **Assembled Watch - Front and Back**
   ![248465391-174d9c86-a782-402c-9f40-d455ebd8f1ef](https://github.com/user-attachments/assets/88d6a27c-0659-45d0-a401-6666e3d667b4)

4. **Service / Tech Puck Exploration**
   ![Screenshot 2024-09-30 174631](https://github.com/user-attachments/assets/f66506e5-2965-4dd6-ac76-fcacb692d002)
   ![211921454-efc67dd0-3a86-407a-a53b-dbce7d059ead](https://github.com/user-attachments/assets/1e383d4d-ad63-4f46-b15b-b5678c955e0d)

5. **Additional Visuals**
   ![241123783-0ecd49ee-87ff-4cde-9060-24d48c5cfade](https://github.com/user-attachments/assets/723f9d1d-d55b-43e2-903b-58e9a6d527c5)
   ![241123687-09d4c374-2d0c-455f-a919-4a59138ad10e (1)](https://github.com/user-attachments/assets/98daed2b-03cf-461d-a02b-3312617687c1)
   ![248465139-50e438e8-4756-424c-868c-67f0bfdfedbb](https://github.com/user-attachments/assets/a68f6fce-e5cd-4bab-bd28-738f808581b7)
   ![244199015-1c1b4e0c-4dde-461f-a7b2-ccfb9a86e202](https://github.com/user-attachments/assets/92ec8bbe-2105-4832-90a0-8a6831f65365)
   ![244198923-7aafcdc3-8758-4472-8234-4ef7c5881dfe](https://github.com/user-attachments/assets/8199f988-7c31-4913-b2d4-b22e3f266962)
   ![248467414-c0ff1934-5fe4-4696-9213-ace8d471f633](https://github.com/user-attachments/assets/172599c9-fc08-4d54-b06c-b6f6def764fe)

## License

There is currently no repository-wide license file in this repo. Until one is added, treat the contents as shared for review and contribution discussion, not as a formally licensed open-source release.
