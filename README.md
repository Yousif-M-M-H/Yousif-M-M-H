# Yosif Mohamedain

CS master's student at UTC (graduating May 2027) and research assistant at the Center for Urban Informatics and Progress (CUIP). Most of my work right now is connected-vehicle stuff: getting V2X messages, LiDAR detections, and traffic signal data working together in real time. Before that I spent eight months at SEL writing C#/WPF for their substation diagram tool.

Looking for full-time software engineering roles starting 2027.

## What I'm working on

**TACA: Trust-Aware Conflict Alerting.** Checks whether incoming V2X messages can be trusted by matching each reported object against what the LiDAR actually sees, by position and time. If a message reports a car no sensor picked up, it gets flagged as a ghost. I've built the live SUMO digital twin (LiDAR + signal controller) that acts as ground truth, and now I'm designing the trust scorer.

*Python, SUMO/TraCI, Docker*

## Things I've built

**V2X safety app (CUIP).** React Native app that turns a regular phone into a V2X endpoint, with no in-vehicle hardware. It shows live LiDAR detections and signal data, cleans up jittery and stale ML output on-device, and runs at ~100 ms end-to-end over public cellular across the 12 intersections of Chattanooga's MLK Smart Corridor. This became our IEEE BigData 2025 paper.

**Custom Control Manager (SEL internship).** The import pipeline that lets utilities bring their own XML/SVG controls into acSELerator Diagram Builder without code changes, plus the validation that makes imported controls behave like built-ins. Closed source, so no repo, but happy to talk about it.

**Site documentation app (Nile Technical Agencies).** Flutter + Firebase app for engineers to upload site photos and project details.

## Publication

Y. Hassan\*, **Y. Mohamedain**\*, M. Fadul, A. Harris, M. Sartipi. "Cloud-Based Network-V2X Platform for Improving Road Users Safety." *IEEE BigData 2025.* \*Equal contribution. [doi.org/10.1109/BIGDATA66926.2025.11401956](https://doi.org/10.1109/BIGDATA66926.2025.11401956)

## Stack

**Use most:** Python, C# / .NET (WPF), React Native, SQL
**Also:** JavaScript, Dart/Flutter, Docker, SUMO/TraCI, NUnit, Jenkins, Linux

## Contact

[yosifmohamedain8@gmail.com](mailto:yosifmohamedain8@gmail.com) · [LinkedIn](https://linkedin.com/in/yousif-mohamedain-58aba0209)
