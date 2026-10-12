# Yosif Mohamedain

I build software for connected vehicles at UTC's Center for Urban Informatics and Progress, mostly real-time V2X, LiDAR, and traffic signal data. M.S. Computer Science, graduating May 2027. Looking for full-time SWE roles.

[Email](mailto:yosifmohamedain8@gmail.com) · [LinkedIn](https://linkedin.com/in/yousif-mohamedain-58aba0209) · [Paper](https://doi.org/10.1109/BIGDATA66926.2025.11401956)

<p>
  <img src="https://skillicons.dev/icons?i=py,cs,dotnet,react,js,flutter,docker,git,linux&perline=9" />
</p>

---

### Right now

**TACA: Trust-Aware Conflict Alerting**  
<sub>Python · SUMO/TraCI · LiDAR · Docker</sub>

V2X messages can lie. A spoofed or buggy sender can report a car that isn't there. TACA checks each reported object against what the LiDAR actually sees, matching by position and time, and flags anything with no match as a ghost. The live SUMO digital twin that acts as ground truth is done. Now I'm designing the trust scorer.

<!-- Drop a screenshot or GIF of the digital twin here -->
<!-- <img src="docs/twin.gif" width="640" /> -->

---

### Things I've built

**V2X safety app** · CUIP  
<sub>React Native · Mapbox · iOS/Android</sub>

Turns a regular phone into a V2X endpoint with no in-vehicle hardware. It shows live LiDAR detections and signal timing, and cleans up jittery and stale ML output on the device.

`~100 ms end-to-end` · `12 intersections` · `tested in rain, fog, night, peak traffic`

This became our IEEE BigData 2025 paper.

<!-- <img src="docs/v2x-app.png" width="300" /> -->

**Custom Control Manager** · SEL internship  
<sub>C# · WPF · .NET · NUnit · FlaUI</sub>

An import pipeline that lets utilities add their own XML/SVG controls to acSELerator Diagram Builder without code changes, with validation so imported controls behave like the built-in ones. It's closed source, so there's no repo, but I'm happy to talk through it.

**Site documentation app** · Nile Technical Agencies  
<sub>Flutter · Firebase</sub>

Lets engineers upload site photos and project details to one place instead of scattered chats.

---

### Publication

Y. Hassan\*, **Y. Mohamedain**\*, M. Fadul, A. Harris, M. Sartipi. *Cloud-Based Network-V2X Platform for Improving Road Users Safety.* IEEE BigData 2025. <sub>\*equal contribution</sub>
