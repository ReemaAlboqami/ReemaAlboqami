<h1 align="center">Reema Alboqami</h1>

<p align="center">
  <b>Computer Engineering · Communication Systems · Space Technology</b><br>
  Senior at Taif University · Aramco UIP Alumna
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logoColor=white" alt="MATLAB">
  <img src="https://img.shields.io/badge/Simulink-0076A8?style=flat-square&logoColor=white" alt="Simulink">
  <img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C/C++">
  <img src="https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white" alt="Arduino">
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32">
  <img src="https://img.shields.io/badge/Cisco_Packet_Tracer-1BA0D7?style=flat-square&logo=cisco&logoColor=white" alt="Cisco Packet Tracer">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logoColor=black" alt="Power BI">
</p>

---

I work where hardware meets software, with a focus on embedded systems, control, and communication networks. My goal is a career in space technology.

## Featured projects

### [Satellite Pass Predictor](https://github.com/ReemaAlboqami/satellite-pass-predictor)
`Python` `SGP4` `Orbital Mechanics`

Predicts when a satellite passes over any ground location, using live orbital data.
- Pulls current TLEs from CelesTrak and propagates the orbit with SGP4
- Converts positions to azimuth and elevation for the observer and plots each pass on a sky chart
- Coordinate math checked against reference values with a test suite

### [Filtered PID Controller for a 3DOF Helicopter](https://github.com/ReemaAlboqami/3dof-helicopter-pid)
`MATLAB` `Simulink` `Control Systems`

Designed a filtered PID controller by pole placement to track a 120-second elevation path and survive a 2-second motor blackout.
- Cut the cost function from 105.31 to 2.11 over four tuning iterations
- Recovered from the blackout with zero crash penalty and no actuator saturation
- Diagnosed and fixed integrator windup that caused the first design to crash

### [Smart City Air Quality Monitoring Network](https://github.com/ReemaAlboqami/air-quality-monitoring-network)
`Cisco Packet Tracer` `ESP32` `IoT`

Designed a star-topology sensor network for city-wide air quality monitoring and backed it with a working hardware node.
- Simulated the full network: router, switch, access point, server, and four IoT sensors
- Built an ESP32 node with an MQ135 gas sensor and a live OLED readout

### [Smart Posture Monitor](https://github.com/ReemaAlboqami/smart-posture-monitor)
`Arduino` `C++` `Bluetooth`

A wearable that detects slouching and alerts the user's phone in real time.
- Combined a flex sensor and a 3-axis accelerometer on an Arduino UNO
- Streamed live posture data to Android over an HC-05 Bluetooth link

## Experience

**Aramco, University Internship Program**
- Built a Power BI performance dashboard with custom DAX measures
- Designed a tracking system with live dashboards for a VR training rollout
- Worked on virtual machine deployment and device enrollment

## Beyond coursework

- **AstroNova** space club, Programming and Technology
- **Google Developer Group on Campus**, Taif University
