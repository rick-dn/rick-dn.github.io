---
title: Visual-Inertial Navigation for GPS-Denied Flight
subtitle: In progress
group: "Aakash: Independent Autonomous Flight R&D"
date: 2026-10-29
period: 2024–present
summary: OpenVINS on a simulated ArduPilot quadcopter in a Gazebo warehouse, scored against ground truth on a scripted flight. The first clean run (takeoff, 2 m square, landing; 11.7 m) tracked to 3 cm position RMSE and 0.42° rotation, with +0.9% scale error, a best case on perfect sim sensors. OpenVINS's own 3-sigma was about 10x the real error, so its covariance can't be trusted as it stands. Next, inputs are broken on purpose (timing offsets, IMU noise, dropped or dark frames) to build a health monitor that reports OK / DEGRADED / LOST before the estimate falls apart.
tags: [VIO, OpenVINS, Gazebo, SITL, GPS-Denied]
repo: https://github.com/rick-dn/vin_autonomy
---
