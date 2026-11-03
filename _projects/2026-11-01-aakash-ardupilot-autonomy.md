---
title: "ArduPilot Autonomy: Layered Flight Stack"
group: "Aakash: Independent Autonomous Flight R&D"
date: 2026-11-01
period: 2024–present
summary: A ROS 2 autonomy stack over MAVROS with a three-layer design. A commander arbitrates safety conditions and operator requests, an executive runs one flight sequence at a time, and a stateless flight stack passes every command through four ordered gates (flight mode, safety, armed/in-air state, sanity limits). Includes a browser ground station over MQTT.
tags: [ROS 2, ArduPilot, MAVROS, Safety Architecture, SITL]
youtube: 3HACJgiugbA
repo: https://github.com/rick-dn/ardupilot_autonomy
---
