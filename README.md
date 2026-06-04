<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Tanish%20Y&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=ECE%20%7C%20VLSI%20%7C%20Communication%20Systems%20%7C%20Robotics&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=700&lines=Rank+%231+%E2%80%94+2028+ECE+Batch+%7C+VIT+Chennai;Bridging+Theory+%26+Physical+Implementation)](https://git.io/typing-svg)

<br/>

![CGPA](https://img.shields.io/badge/CGPA-9.78%20%2F%2010-0ea5e9?style=for-the-badge&logo=academia&logoColor=white)
![Batch Rank](https://img.shields.io/badge/Batch%20Rank-%231%20in%20ECE%202028-22c55e?style=for-the-badge&logo=trophy&logoColor=white)
![Institute](https://img.shields.io/badge/VIT%20Chennai-B.Tech%20ECE-f97316?style=for-the-badge&logo=graduation-cap&logoColor=white)

</div>

---

### `> Profile`

```yaml
name        : Tanish Y
location    : Chennai, India
institute   : Vellore Institute of Technology, Chennai
degree      : B.Tech — Electronics & Communication Engineering
batch       : 2024–2028
rank        : #1 in 2024 ECE Batch | CGPA 9.78

role        : Electrical & Electronics Lead @ Dreadnought Robotics
competing   : International AUV competition — TAC Challenge, Norway

passion     : Bridging theory and physical implementation
              CMOS circuit design ↔ real-time firmware ↔ communication systems
```

> *"I build things that work underwater, in the air, and inside silicon."*



---

## 🛠 Tech Stack & Tools

<table>
<tr>
<td valign="top" width="33%">

**⚙️ Hardware & Design**

![Cadence](https://img.shields.io/badge/Cadence%20Virtuoso-EDA%20Design-c026d3?style=flat-square&logo=cadence&logoColor=white)
![KiCAD](https://img.shields.io/badge/KiCAD-PCB%20Design-314cb0?style=flat-square&logo=kicad&logoColor=white)
![GNU Radio](https://img.shields.io/badge/GNU%20Radio-SDR%20%26%20Comms-2563eb?style=flat-square)

</td>
<td valign="top" width="33%">

**💻 Programming**

![Verilog](https://img.shields.io/badge/Verilog%20HDL-RTL%20Design-ef4444?style=flat-square)
![Python](https://img.shields.io/badge/Python-Scripting%20%26%20Dashboards-3b82f6?style=flat-square&logo=python&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-Signal%20%26%20Systems-f59e0b?style=flat-square)
![Java](https://img.shields.io/badge/Java-OOP-e67e22?style=flat-square&logo=openjdk&logoColor=white)

</td>
<td valign="top" width="33%">

**🔬 Fabrication**

![PCB](https://img.shields.io/badge/PCB%20Design-Layout%20%26%20Routing-0f172a?style=flat-square)
![BMS](https://img.shields.io/badge/Battery%20Management-Systems-dc2626?style=flat-square)
![Soldering](https://img.shields.io/badge/Soldering%20%26%20Spot%20Welding-Assembly-78716c?style=flat-square)

</td>
</tr>
</table>

---

## 🚀 Featured Projects

> Click any project to expand — from quantum circuits to subsea electronics.

<details>
<summary><b>🤿 Autonomous Underwater Vehicle (AUV) &nbsp;—&nbsp; <i>TAC Challenge, Norway</i></b></summary>
<br/>

```
Domain  : Robotics / Embedded Systems / Power Electronics
Stack   : Jetson Orin Nano · Pixhawk 2.4.8 · I2C · UART · BMS · KiCAD
Role    : Electrical & Electronics Lead
```

International competition AUV built ground-up with complete electrical ownership.

| Subsystem | Details |
|-----------|---------|
| **Compute** | Jetson Orin Nano + Pixhawk 2.4.8 as onboard brain and flight controller |
| **Actuation** | Brushless thrusters with depth sensors & IMU for closed-loop navigation |
| **Electrical Architecture** | Full power distribution network, BMS, watertight electronics enclosure rated for subsea depth |
| **Integration** | Sensor/actuator interfacing over I²C and serial buses; end-to-end hardware validation across sub-teams |

`Jetson Orin` `Pixhawk` `BMS` `PCB Design` `I2C` `Subsea Electronics`

</details>

---

<details>
<summary><b>🧠 In-Memory Computation using 6T SRAM Cell Array &nbsp;—&nbsp; <i>180nm CMOS, Cadence Virtuoso</i></b></summary>
<br/>

```
Domain  : VLSI / Digital Design / In-Memory Computing
Stack   : Cadence Virtuoso · 180nm CMOS · Verilog · Transient Simulation
Status  : Scaling to 16×16 | RISC architecture in ideation
```

> Exploiting bitline encoding to perform Boolean logic **directly inside memory** — no ALU required.

- Designed transistor-level **6T SRAM cell** satisfying read stability and write-ability constraints; verified via transient simulation
- Built **4×4 array** and characterized BL/BLB analog voltages across all data combinations for 1–4 simultaneous wordline activations
- Implemented **AND, OR, XOR** logic directly within the array using bitline encoding
- Designed threshold-tuned **Computational Sense Amplifier** (skewed inverter) with 4:1 and 2:1 MUX trees
- Scaling to **16×16 with XOR support**; early-stage ideation of a RISC architecture using the IMC array as a compute primitive

`Cadence Virtuoso` `180nm CMOS` `SRAM` `In-Memory Computing` `Sense Amplifier` `Verilog`

</details>

---

<details>
<summary><b>📡 Dynamic 5G Bandwidth Allocation using QAOA &nbsp;—&nbsp; <i>Quantum ML</i></b></summary>
<br/>

```
Domain  : Quantum Computing / 5G / Signal Processing
Stack   : Qiskit · FastAPI · MongoDB · GNU Radio
```

> Solving a combinatorial NP-hard scheduling problem with quantum circuits — then visualizing it in GNU Radio.

- Formulated **5G PRB allocation** as a constrained combinatorial optimization problem
- Implemented **QAOA circuits in Qiskit** and benchmarked against classical greedy scheduling
- Simulated heterogeneous traffic (video / browsing / gaming / chat) with **FastAPI + MongoDB** backend for real-time demand management
- Converted allocation outputs to **baseband signals** and visualized spectrum behavior in **GNU Radio**

`Qiskit` `QAOA` `GNU Radio` `FastAPI` `MongoDB` `5G` `Signal Processing`

</details>

---

<details>
<summary><b>🚁 Quadcopter with Custom Flight Controller &nbsp;—&nbsp; <i>ESP32, Q330 Frame</i></b></summary>
<br/>

```
Domain  : Embedded Systems / Control Systems / Robotics
Stack   : ESP32 · Dual-core RTOS · I2C · PWM · WiFi
```

> **Zero commercial firmware.** Every line of flight logic written from scratch.

- Raw **I²C sensor reads**, complementary filter at **500 Hz** for roll/pitch/yaw estimation
- **Cascaded PID** attitude and rate loops with hardware **PWM ESC** output
- **2000-sample boot-time gyro/accel calibration** + 80 Hz LPF for motor vibration rejection
- Asymmetric motor mixing for Q330's non-symmetric frame geometry
- **Dual-core architecture** with WiFi web-based Ground Control Station hosted directly on the drone

`ESP32` `PID Control` `IMU` `Embedded C` `PWM` `Dual-core RTOS`

</details>

---

<details>
<summary><b>🔵 Underwater Optical Communication Link &nbsp;—&nbsp; <i>4-PPM, Dual ESP32</i></b></summary>
<br/>

```
Domain  : Optical Communications / Embedded Systems / Signal Processing
Stack   : ESP32 · Python · WebSocket · Beer-Lambert Propagation Model
```

> Beer-Lambert optics meets pulse-position modulation in a full end-to-end hardware prototype.

- Transistor-driven **650 nm laser transmitter** encoding live BMP280 barometric altitude into **4-PPM optical pulse timing**
- **Auto-calibrated LDR receiver** decoding inter-pulse delays for data recovery
- Grounded in **Beer-Lambert propagation** (`sr = st · e⁻ᶜᵈ`) and blue-green optical window theory (400–550 nm)
- Dual real-time dashboards: **Python desktop (5 Hz)** + **WebSocket browser (4 Hz)** — live max error and rolling error % over 300 samples

`ESP32` `4-PPM` `UWOC` `BMP280` `Python` `WebSocket` `Optics`

</details>

<details>
<summary><b>⚙️ Other Projects</b></summary>
<br/>

| Project | Description |
|---------|-------------|
| 🤖 **Line Maze Solving Robot** | Autonomous navigation through mazes using line-following logic |
| 📟 **Morse Code Decoder** | Hardware/firmware decoder for real-time Morse input |
| 🚦 **Traffic Light Controller** | FSM-based controller implemented in HDL |
| 💧 **Liquid Turbidity Tracker** | Optical sensor system for real-time water clarity monitoring |

</details>

---

## 💼 Experience

```
🤖  Dreadnought Robotics                                         Chennai, India
    │
    ├── ⚡ Electrical & Electronics Lead         [Feb 2026 – Present]
    │     Guiding PCB design, circuit debugging & system integration.
    │     Overseeing full electrical architecture for AUV @ international competition.
    │
    └── 🔧 Team Member                           [Jul 2025 – Feb 2026]
          Power distribution, BMS, sensor interfacing, hardware validation.
          Cross-team collaboration across software & mechanical sub-teams.
```

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tanishy2006&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&text_color=94a3b8" height="150"/>

<br/><br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=tanishy2006&theme=tokyonight&hide_border=true&background=0d1117&ring=38bdf8&fire=f97316&currStreakLabel=38bdf8)](https://git.io/streak-stats)

</div>

---

## 🌐 Languages

<div align="center">

![English](https://img.shields.io/badge/English-Professional-0ea5e9?style=flat-square)
![Tamil](https://img.shields.io/badge/Tamil-Native-22c55e?style=flat-square)
![Hindi](https://img.shields.io/badge/Hindi-Native-f59e0b?style=flat-square)
![Spanish](https://img.shields.io/badge/Spanish-Elementary-a78bfa?style=flat-square)

</div>

---

## 📫 Connect with Me

<div align="center">

[![Email](https://img.shields.io/badge/tanishy2006@gmail.com-Email-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tanishy2006@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tanish-y-248a8130b/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tanishy2006)
[![Phone](https://img.shields.io/badge/+91%209677263450-Call-25d366?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:+919677263450)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" width="100%"/>

*"Hardware is just software with consequences."*

![Profile Views](https://komarev.com/ghpvc/?username=tanishy2006&color=38bdf8&style=flat-square&label=Profile+Views)

</div>
