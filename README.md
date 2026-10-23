
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:0B1220,55:123047,100:0891B2&section=header&text=SURYA%20K&fontSize=58&fontColor=E6FCFF&fontAlignY=38&desc=ENGINEERING%20SYSTEMS%20%2F%20FROM%20SENSORS%20TO%20SILICON&descAlignY=60&descSize=14&animation=fadeIn" width="100%" alt="Surya K — Engineering Systems"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=2600&pause=850&color=67E8F9&center=true&vCenter=true&width=850&lines=Embedded+Systems+%2F+Real-Time+Firmware;Robotics+%2F+Autonomy+%2F+ROS+2;RTL+Design+%2F+Verification+%2F+PIM;Hardware+%E2%86%94+Software+%E2%86%94+The+Physical+World" alt="Areas of engineering focus"/>
</p>

<p align="center">
  <a href="mailto:kksurya2023@gmail.com">
    <img src="https://img.shields.io/badge/EMAIL-0B1220?style=flat-square&logo=gmail&logoColor=67E8F9" alt="Email"/>
  </a>
  <a href="https://www.linkedin.com/in/suryak23/">
    <img src="https://img.shields.io/badge/LINKEDIN-0B1220?style=flat-square&logo=linkedin&logoColor=67E8F9" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/suryak26">
    <img src="https://img.shields.io/badge/GITHUB-0B1220?style=flat-square&logo=github&logoColor=67E8F9" alt="GitHub"/>
  </a>
  <img src="https://img.shields.io/badge/CHENNAI%2C%20INDIA-0B1220?style=flat-square&logo=googlemaps&logoColor=67E8F9" alt="Location"/>
</p>

---

## `00 / THE ENGINEERING MINDSET`

I'm Surya, an Electronics and Communication Engineering undergraduate at Sri Venkateswara College of Engineering, Chennai.

I work across embedded firmware, robotic systems, Industrial IoT, and digital hardware architecture. I'm interested in the point where software meets physical constraints: timing, power, communication, motion, and verification.

My approach is simple:

**Understand the system. Build the interface. Verify the result.**

Currently working on embedded systems and Industrial IoT at **OliveIoT**.

---

## `01 / SYSTEM MAP`

The engineering space I work in spans several layers, from physical signals to firmware, communication, robotics, and hardware architecture.

```mermaid
%%{init: {"theme":"base","themeVariables":{"background":"#0B1220","primaryColor":"#102A43","primaryTextColor":"#E6FCFF","primaryBorderColor":"#22D3EE","lineColor":"#22D3EE","secondaryColor":"#123047","tertiaryColor":"#0F172A","fontFamily":"monospace"}}}%%
flowchart LR
    A["01 / PHYSICAL<br/>Sensors + Actuators"]
    B["02 / EMBEDDED<br/>STM32 + ESP32 + RTOS"]
    C["03 / CONNECTIVITY<br/>UART + SPI + I2C + RS485"]
    D["04 / EDGE & ROBOTICS<br/>Linux + ROS 2 + Vision"]
    E["05 / DIGITAL DESIGN<br/>Verilog + LUT-based PIM"]
    F["06 / VERIFICATION<br/>Golden Models + Netlists"]

    A --> B
    B <--> C
    B <--> D
    E --> F

    classDef cyan fill:#102A43,stroke:#22D3EE,color:#E6FCFF,stroke-width:1.5px;
    class A,B,C,D,E,F cyan;
```

<p align="center">
  <sub>Different disciplines. One engineering mindset.</sub>
</p>

---

## `02 / SELECTED BUILDS`

These projects represent different sides of my work: hardware-aware architecture, real-time robotics, inspection systems, and connected embedded devices.

<table>
  <tr>
    <td width="50%" valign="top">
      <p align="center">
        <img src="https://raw.githubusercontent.com/suryak26/SILG/main/ASP_LUT/netlist/asplut_netlist.png" width="100%" alt="ASPLUT mapped RTL netlist"/>
      </p>
      <h3>01 / ASPLUT</h3>
      <p><b>Near-Memory LUT Generator</b></p>
      <p>Exploring a serial-parallel architecture for lookup-table-centric Processing-in-Memory inference.</p>
      <p>
        <img src="https://img.shields.io/badge/Verilog-0B1220?style=flat-square&logo=verilog&logoColor=67E8F9" alt="Verilog"/>
        <img src="https://img.shields.io/badge/RTL-0B1220?style=flat-square&logoColor=67E8F9" alt="RTL"/>
        <img src="https://img.shields.io/badge/Python-0B1220?style=flat-square&logo=python&logoColor=67E8F9" alt="Python"/>
      </p>
      <ul>
        <li>28,672 LUT entries validated against an independent Python reference model, with zero mismatches.</li>
        <li>37.7% lower mapped-netlist area.</li>
        <li>51.8% lower reported total power.</li>
        <li>45.2% improvement in derived maximum frequency.</li>
      </ul>
      <p><a href="https://github.com/suryak26/SILG/tree/main/ASP_LUT"><b>Explore the RTL and verification work →</b></a></p>
    </td>
    <td width="50%" valign="top">
      <p align="center">
        <img src="https://raw.githubusercontent.com/suryak26/Hexapod/main/Hexapod%20Robot%20-%203463845/images/Whole_Thing_With_Remote.jpg" width="100%" alt="Hexapod robot prototype with its controller"/>
      </p>
      <h3>02 / HEXAPOD</h3>
      <p><b>Real-Time Multi-Legged Robotics</b></p>
      <p>A two-level control architecture combining deterministic low-level motion control with higher-level robotics software.</p>
      <p>
        <img src="https://img.shields.io/badge/STM32-0B1220?style=flat-square&logo=stmicroelectronics&logoColor=67E8F9" alt="STM32"/>
        <img src="https://img.shields.io/badge/Zephyr_RTOS-0B1220?style=flat-square&logo=zephyrproject&logoColor=67E8F9" alt="Zephyr RTOS"/>
        <img src="https://img.shields.io/badge/ROS_2-0B1220?style=flat-square&logo=ros&logoColor=67E8F9" alt="ROS 2"/>
      </p>
      <ul>
        <li>18-servo, six-legged robotic platform.</li>
        <li>Closed-form inverse kinematics.</li>
        <li>Tripod, ripple, and wave gait generation with 50 Hz motion updates.</li>
        <li>Custom PCB integration and ROS 2 / Gazebo simulation.</li>
      </ul>
      <p><a href="https://github.com/suryak26/Hexapod"><b>Explore the robotics stack →</b></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <p align="center">
        <img src="https://raw.githubusercontent.com/suryak26/Roctara/main/IMG-20250930-WA0035.jpg" width="100%" alt="Roctara wall-climbing robot project"/>
      </p>
      <h3>03 / ROCTARA</h3>
      <p><b>Wall-Climbing Inspection Robot</b></p>
      <p>A modular inspection platform designed around improved suction, wireless control, and computer vision.</p>
      <p>
        <img src="https://img.shields.io/badge/Embedded_C-0B1220?style=flat-square&logo=c&logoColor=67E8F9" alt="Embedded C"/>
        <img src="https://img.shields.io/badge/ROS-0B1220?style=flat-square&logo=ros&logoColor=67E8F9" alt="ROS"/>
        <img src="https://img.shields.io/badge/OpenCV-0B1220?style=flat-square&logo=opencv&logoColor=67E8F9" alt="OpenCV"/>
      </p>
      <ul>
        <li>EDF-based suction replacing the earlier propeller-based design.</li>
        <li>RF-based wireless control and geared motor actuation.</li>
        <li>YOLO26n-seg and OpenCV-based crack measurement workflow.</li>
        <li>ROS and Gazebo work toward autonomous inspection.</li>
      </ul>
      <p><a href="https://github.com/suryak26/Roctara"><b>Explore the inspection platform →</b></a></p>
    </td>
    <td width="50%" valign="top">
      <p align="center">
        <img src="https://raw.githubusercontent.com/suryak26/Motor-Health-Monitoring-System/main/docs/Architecture_Diagram.png" width="100%" alt="Motor health monitoring system architecture"/>
      </p>
      <h3>04 / MOTOR HEALTH</h3>
      <p><b>Embedded Condition Monitoring</b></p>
      <p>A connected monitoring workflow that turns electrical and mechanical measurements into actionable operating states.</p>
      <p>
        <img src="https://img.shields.io/badge/ESP32-0B1220?style=flat-square&logo=espressif&logoColor=67E8F9" alt="ESP32"/>
        <img src="https://img.shields.io/badge/UART-0B1220?style=flat-square&logoColor=67E8F9" alt="UART"/>
        <img src="https://img.shields.io/badge/Firebase-0B1220?style=flat-square&logo=firebase&logoColor=67E8F9" alt="Firebase"/>
      </p>
      <ul>
        <li>Current, temperature, and vibration sensing.</li>
        <li>Threshold-based good, warning, and fault classification.</li>
        <li>Local LED and buzzer alerts.</li>
        <li>Firebase integration for remote data access.</li>
      </ul>
      <p><a href="https://github.com/suryak26/Motor-Health-Monitoring-System"><b>Explore the monitoring system →</b></a></p>
    </td>
  </tr>
</table>

<sub>ASPLUT results are from the reported comparison against an identically constrained baseline. The frequency figure is derived from the evaluation; these figures should not be interpreted as measurements from fabricated silicon.</sub>

---

## `03 / THE WORKBENCH`

<table>
  <tr>
    <td width="25%"><b>FIRMWARE</b></td>
    <td>C · C++ · STM32 · ESP32 · FreeRTOS · Zephyr · GPIO · Peripheral Drivers</td>
  </tr>
  <tr>
    <td><b>COMMUNICATION</b></td>
    <td>UART · SPI · I²C · RS485 · Modbus · LoRa · Ethernet · TCP/IP</td>
  </tr>
  <tr>
    <td><b>ROBOTICS</b></td>
    <td>ROS · ROS 2 · Gazebo · RViz · Inverse Kinematics · SLAM</td>
  </tr>
  <tr>
    <td><b>DIGITAL DESIGN</b></td>
    <td>Verilog · Icarus Verilog · RTL Verification · Python Golden Models</td>
  </tr>
  <tr>
    <td><b>EDGE & VISION</b></td>
    <td>Linux · Raspberry Pi · Python · OpenCV · YOLO26 · Flask</td>
  </tr>
  <tr>
    <td><b>HARDWARE TOOLS</b></td>
    <td>KiCad · Proteus · LTspice · STM32CubeIDE · STM32CubeMX</td>
  </tr>
</table>

---

## `04 / BEYOND THE BENCH`

Engineering isn't only firmware and circuit boards. I've also contributed to collaborative, public-facing event platforms.

- [Make-A-Thon 7.0](https://make-a-thon-7.in/) — event platform development.
- [UPAGRAHA '26](https://upagraha26.in/) — website development and frontend refinement.
- [Makeathon source repository](https://github.com/suryak26/Makeathon).

I also gained electronics manufacturing exposure at **Syrma SGS Technology Ltd**, including PCB assembly, inspection, testing, RFID manufacturing, and quality processes.

---

## `05 / SIGNALS OF PROGRESS`

| Milestone | Result |
|---|---|
| Hackerz'26 — SeedStart | Top 15 among 530+ registrations |
| Sprinthathon'25 | Top 100 among 3,500+ teams |
| IMPULSE'26 | Winner, Project Presentation |
| Upagraha'25 | First Place, Blind Chase |
| ZEPHORIA'25 | Winner, Project Expo |

**Education:** B.E. Electronics and Communication Engineering, Sri Venkateswara College of Engineering · 2023–2027 · CGPA 8.06/10

---

## `06 / ENGINEERING PRINCIPLES`

```text
01  Build across boundaries.
    Hardware, firmware, networks, and applications must work together.

02  Verify with evidence.
    Simulations, reference models, measurements, and repeatable tests matter.

03  Be precise about progress.
    Completed, under development, and planned are different states.

04  Optimize with context.
    Area, power, timing, reliability, and complexity are trade-offs.
```

---

## `07 / ESTABLISH CONTACT`

Interested in embedded firmware, real-time systems, robotics, Industrial IoT, and hardware-software integration.

<p align="center">
  <a href="mailto:kksurya2023@gmail.com">
    <img src="https://img.shields.io/badge/CONTACT-0B1220?style=for-the-badge&logo=gmail&logoColor=67E8F9" alt="Contact by email"/>
  </a>
  <a href="https://www.linkedin.com/in/suryak23/">
    <img src="https://img.shields.io/badge/CONNECT-0B1220?style=for-the-badge&logo=linkedin&logoColor=67E8F9" alt="Connect on LinkedIn"/>
  </a>
</p>

<p align="center">
  <sub>Designed around a simple idea: make the system work, then make the result measurable.</sub>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=0:0891B2,100:0B1220" width="100%" alt=""/>
</p>
