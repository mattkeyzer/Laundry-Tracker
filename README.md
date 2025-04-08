# 🧺 Laundry Notification System 📱

## Overview

This project allows you to monitor and control your washing machine and dryer remotely using **Sonoff S31 Smart Plugs** running **Tasmota** firmware. The application runs on a **Raspberry Pi**, continuously polling the power usage of your laundry equipment to determine their status. It sends notifications when the washing machine or dryer starts or finishes a cycle.

### **Features:**
- Monitors power usage of the washing machine and dryer.
- Sends SMS notifications (via Verizon's vText service) when the washing machine or dryer starts and finishes.
- Runs on a Raspberry Pi using Python.
- Automatically restarts the application on Raspberry Pi reboot using a **cron job**.
- Easily configurable code for DIY deployment.
