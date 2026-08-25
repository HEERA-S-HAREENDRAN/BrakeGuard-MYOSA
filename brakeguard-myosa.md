---
publishDate: 2026-08-25
title: BrakeGuard - A Continuous IoT-Based Capacitive Brake Fluid Moisture Health Monitoring System
excerpt: BrakeGuard is a low-cost embedded safety system that monitors brake fluid moisture and braking conditions to identify brake-fluid degradation and provide an early indication of brake fade risk.
image: 
tags:
  - smart-sensing
  - condition-monitoring
  - automotive-safety
  - edge-iot
  - sensor-fusion
---
> Continuous brake-fluid health monitoring for safer, condition-based brake maintenance.
---
## Acknowledgements
This project was developed using the MYOSA Mini Kit and its sensor ecosystem as part of the IEEE Sensors Council MYOSA 6.0 Global Student Competition. We acknowledge the MYOSA platform for providing the embedded hardware and sensor modules that enabled the development and testing of BrakeGuard. We also thank our mentor Dr.Rajesh Kannan Megalingam for his support and encouragement during the prototyping and validation process.
## Overview

Brake fluid is a critical yet often overlooked part of a vehicle's braking system. Glycol-based brake fluids such as DOT 3, DOT 4, and DOT 5.1 gradually absorb moisture from their surroundings. As moisture increases, the fluid's boiling point decreases and the risk of thermal degradation and internal corrosion increases. Despite this continuous degradation, brake-fluid condition is typically assessed only during periodic maintenance, providing no continuous view of how the fluid is changing between service intervals.

BrakeGuard addresses this gap by converting brake-fluid condition into a continuously monitored safety parameter. A capacitive sensing unit detects changes in the electrical properties of the fluid associated with moisture contamination, while the ESP32-based MYOSA Mini Kit processes the measurement alongside braking-event data from the MPU6050 and environmental data from the BMP180.

Instead of reporting moisture content alone, BrakeGuard combines these measurements and evaluates them against experimentally established thresholds to generate a Brake Fade Risk Index. The resulting status is presented locally through the MYOSA OLED and can also be transmitted for remote monitoring and trend analysis.

The project demonstrates a low-cost approach to condition-based brake-fluid monitoring, bringing together capacitive sensing, sensor fusion, edge processing, and IoT telemetry to make a normally invisible maintenance concern measurable and actionable.
## Demo / Examples

### Images

<!-- Add project images here once the final prototype and testing results are available. -->

### Videos

<!-- Add the project demonstration video here once available. -->
