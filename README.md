# Smart Fall-Detection Bracelet for Elderly Safety
**Course:** Engineering Design – MT5T3  
**Institution:** York University  
**Team:** Section M, Tutorial #5, Team #3  
**Date:** 2026

## Overview
A wrist-worn smart bracelet that combines accelerometer and heart-rate 
sensor data to automatically detect falls in elderly users and send 
emergency alerts to caregivers no button press required.

## The Problem
Elderly individuals fear falling and going unnoticed. Existing devices 
either require user interaction, cause too many false alarms, or are 
uncomfortable to wear daily.

## Our Solution
A bracelet that fuses motion AND physiological data for more reliable 
detection. When a fall is detected, an automatic alert is sent to a 
caregiver immediately.

## Design Process
Problem → User Research → Concept Generation → Weighted Scoring → Prototype → Testing

Three concepts were evaluated across five weighted criteria:
- Feasibility (38%)
- Desirability (26%)
- Viability (24%)
- Responsibility (10%)
- Creativity (2%)

**Concept A (Smart Bracelet) scored highest at 4.28/5** and was selected 
for prototyping.

## Prototype Iterations
**Version 1 – Motion only:** Accelerometer-based detection. 
Result: high false alarm rate from everyday movements.

**Version 2 – Motion + Heart Rate:** Combined sensor logic.  
Result: significantly reduced false alarms and faster response time.

## Key Findings
- 96% fall detection accuracy over 100 controlled trials
- Comfort rating: 9.1/10 from elderly user testing
- Ease-of-use rating: 8.2/10 from elderly user testing
- Dual-trigger FSM (linear + angular acceleration) 
  significantly reduced false alarms vs motion-only detection

## Tech & Methods
- Accelerometer + heart-rate sensor
- Weighted concept scoring matrix
- Iterative prototyping and user-centered design
- Sensor performance analysis (angular vs. linear acceleration)

## My Role
Contributed to design context write-up, prototype code development, 
poster layout, and team coordination across all phases.

## Future Enhancements
- ML model trained on real fall data to improve accuracy
- Caregiver mobile app for alert management
- Blood oxygen and irregular heart rhythm monitoring
- Multi-day battery optimization
