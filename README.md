# Underwater Vehicle

A low-cost, compact underwater vehicle designed and fabricated for a timed underwater course, focusing on waterproofing, buoyancy control, propulsion efficiency, and directional stability.

## Project Overview

The vehicle was designed and fabricated with a streamlined waterproof body and an integrated electronics system for underwater operation. The design incorporated adjustable ballast and optimized internal component placement to achieve stable underwater motion and efficient propulsion.

The vehicle was controlled wirelessly using an ESP32-based Bluetooth control system and tested on a fixed underwater course.

## Key Features

- Waterproof and lightweight vehicle body
- ESP32-based Bluetooth control
- Dual DC motor propulsion
- L298N motor driver for motor control
- Adjustable ballast system for buoyancy and trim adjustment
- Optimized internal electronics layout
- Sealed electronics compartment for water protection
- Streamlined body to reduce hydrodynamic drag

## Components

| Component | Specification |
|---|---|
| Microcontroller | ESP32 |
| Motor Driver | L298N |
| Motors | 2 × Mini 385 DC Motors |
| Battery | 3-cell NMC 18650 Li-ion pack, 2500 mAh |
| Hull | Lightweight PVC / bottle-based enclosure |
| Propulsion | Dual propeller system |
| Buoyancy | Adjustable ballast + foam |

## Design Considerations

### 1. Waterproofing
- Sealed electronics and electrical connections to prevent water ingress.
- Removable sections designed with sealing provisions for maintenance.

### 2. Buoyancy & Stability
- Adjustable ballast used to achieve near-neutral buoyancy.
- Internal mass distribution optimized for stable underwater movement.
- Foam elements used for additional buoyancy adjustment.

### 3. Hydrodynamic Design
- Streamlined body geometry to reduce drag.
- Smooth external surfaces to improve underwater flow.
- Propulsion system positioned for effective thrust generation.

### 4. Electronics Layout
- Internal components arranged to utilize the available space efficiently.
- Battery, motor driver, and ESP32 positioned within the sealed electronics compartment.
- Wiring kept compact to reduce clutter and power losses.

## Control System

The ESP32 provides wireless Bluetooth control of the vehicle. User commands are transmitted to the ESP32, which controls the motors through the L298N motor driver.

```text
Bluetooth Controller
        ↓
      ESP32
        ↓
   L298N Driver
      ↓    ↓
   Motor  Motor
      ↓    ↓
 Propeller Propeller


<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/8ddfd34f-51b1-4c25-8875-28049887d2ad" />

<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/345cae4a-7dd8-46ac-a7be-0a03bc496c63" />

https://github.com/user-attachments/assets/88115eb8-f93d-49ad-b3db-979f8224c284


