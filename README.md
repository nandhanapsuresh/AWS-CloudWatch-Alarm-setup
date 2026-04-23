# AWS CloudWatch Dashboard & Alarm Setup

## Overview
This project demonstrates how to monitor EC2 CPU metrics using AWS CloudWatch,
create a dashboard, and set up an alarm with SNS email notifications.

## Steps Covered
1. Launch EC2 Instance (cw-demo)
2. Generate CPU Load using `stress` tool
3. Create CloudWatch Dashboard (demo-dashboard)
4. Create CloudWatch Alarm (cpu-high-alarm) — triggers at >70% CPU
5. Configure SNS Email Notification (cw-alert-topic)
6. Test the alarm and verify email alert

## Screenshots
(See `/screenshots` folder)

## Tools Used
- AWS EC2 (t2.micro)
- AWS CloudWatch
- AWS SNS
- stress (Linux load testing tool)
