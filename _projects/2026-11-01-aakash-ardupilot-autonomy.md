---
title: "ArduPilot Autonomy: Layered Flight Stack"
group: "Aakash: Independent Autonomous Flight R&D"
date: 2026-11-01
period: 2024–present
summary: A ROS 2 autonomy stack over MAVROS with a three-layer design. A commander evaluates safety conditions and selects which sequence runs, operator-requested or safety (SRTL, RTL, LAND); an executive holds the sequences and runs one at a time; and a stateless flight stack acts only on the latest command, checks through an FSM that it is permitted in the current flight mode and armed/in-air state, and sanity-checks its arguments. Includes a browser ground station over MQTT.
tags: [ROS 2, ArduPilot, MAVROS, Safety Architecture, SITL]
youtube: 3HACJgiugbA
repo: https://github.com/rick-dn/ardupilot_autonomy
---
