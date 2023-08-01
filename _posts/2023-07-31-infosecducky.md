---
title: Mac Ducky Script For User Security Test
date: 2023-07-30 14:30:00 -0500
categories: [Portfolio, Coding Projects]
tags: [portfolio, coding projects, cybersecurity, duckyscript, flipper zero, red team]     # TAG names should always be lowercase
image:
  path: /assets/ducky.png
---

# Infosec User Test Ducky Script

Ducky Script for testing if end users will plug in a random usb (ducky) or cable(o.mg).

1) When the device is plugged in the payload triggers, it collects the logged in user name and the serial number of device.

2) It then sends that info to a discord webhook
<img src="https://user-images.githubusercontent.com/112792126/209692167-1a0081d4-9446-42cb-bf51-5d1c93d0711c.png">


3) User gets a popup telling them they failed the evaluation and to return the device to the team.
<img src="https://user-images.githubusercontent.com/112792126/209692487-6c9de450-f84f-409e-8b7a-c84e0d31144e.png">

  
# Technology Used

- Understanding of MacOS & Shell
- Duckyscript to write code
- Discord Webhooks
- O.MG Cable & Flipper Zero (BadUSB) to test script deployment
