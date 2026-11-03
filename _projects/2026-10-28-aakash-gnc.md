---
title: "GNC: Fault Injection and Sensor Fusion"
group: "Aakash: Independent Autonomous Flight R&D"
date: 2026-10-28
period: 2024–present
summary: GPS cut mid-hover, the vehicle switched EKF3 to optical flow in 1.3 s and held a 56 s hover with 0.52 m mean error. A scripted nine-fault EKF3 matrix (five runs each) exposed and fixed a gap in ArduPilot's stock GPS/flow switching script, and a from-scratch 15-state error-state EKF rejected a 5 m GPS glitch for the full minute where EKF3 gave in after 10 s.
tags: [GNC, EKF, Sensor Fusion, Fault Injection, ArduPilot]
youtube: muZEITKe7_o
repo: https://github.com/rick-dn/gnc_autonomy
---
