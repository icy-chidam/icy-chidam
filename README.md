<!--
GitHub Profile README
Place this file at the root of a PUBLIC repository named exactly: icy-chidam
-->

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0B1220,45:164E63,100:22D3EE&text=Chidambaresh%20N&fontColor=F8FAFC&fontSize=52&fontAlignY=38&desc=RTL%20Design%20%7C%20VLSI%20%7C%20FPGA%20%7C%20Hardware%20Security&descSize=16&descAlignY=59&animation=fadeIn" alt="Chidambaresh N — RTL Design, VLSI, FPGA and Hardware Security" />

  <p>
    <a href="https://github.com/icy-chidam"><img src="https://img.shields.io/badge/GitHub-icy--chidam-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
    <a href="https://www.linkedin.com/in/chidambareshn/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <img src="https://img.shields.io/badge/Focus-Digital%20Hardware-0F766E?style=for-the-badge" alt="Focus: Digital Hardware" />
  </p>

  <p><em>Turning digital design concepts into testable RTL, FPGA prototypes, and silicon-oriented implementations.</em></p>
</div>

---

## About

I’m a recent Electronics and Communication Engineering graduate interested in building digital hardware from the RTL level through implementation. My work spans **Verilog/SystemVerilog**, FPGA-based systems, RTL-to-GDSII design flows, embedded hardware, and security-aware digital design.

I enjoy projects where architecture and implementation meet: defining a hardware block, reasoning about its behaviour, verifying it with simulations, and understanding the trade-offs that affect area, timing, power, and integration.

- **Primary interests:** RTL design, FPGA prototyping, digital ASIC implementation, and hardware security
- **Adjacent interests:** RISC-V/SHakti systems, neuromorphic hardware, radar-based sensing, and efficient edge computing
- **Engineering approach:** modular design, reproducible tests, clear documentation, and measurable results

## Technical Focus

| Area | Tools and concepts |
|---|---|
| **RTL & Digital Design** | Verilog, SystemVerilog, combinational/sequential logic, FSMs, datapaths, register-mapped IP, AXI4-Lite |
| **Simulation & Debug** | Testbenches, waveform-based debugging, ModelSim/Questa-style workflows, GTKWave |
| **FPGA & SoC** | AMD/Xilinx FPGA workflows, Artix-7, peripheral integration, SHAKTI/RISC-V-based systems |
| **ASIC Implementation** | Synthesis, timing and implementation analysis, RTL-to-GDSII concepts, OpenLane, Sky130, Synopsys Design Compiler / IC Compiler workflows |
| **Embedded & Hardware Applications** | C, Python, UART/SPI, sensor interfaces, radar-based detection, hardware-oriented ML concepts |
| **Development** | Git, Linux, command-line workflows, technical documentation |

> The tools listed reflect the areas I have worked with or explored in projects; they are not a claim of equal proficiency across every tool.

## Featured Repositories

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/icy-chidam/tt_chidam_secengine">Tiny Secure Telemetry Engine</a></h3>
      <p>A TinyTapeout RTL project exploring a compact, mode-selectable hardware block for telemetry-oriented data processing, PRNG generation, CRC-8, and key-stir logic.</p>
      <p><sub>Verilog · Digital design · Hardware security</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/icy-chidam/tt_chidam_binary_detector">8-bit Symmetry Detector</a></h3>
      <p>A combinational pattern detector that compares mirrored bit positions, flags symmetric inputs, and reports the number of mismatched bit pairs.</p>
      <p><sub>Verilog · Combinational logic · Testbench</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/icy-chidam/5_days_rtl2gdsII">RTL-to-GDSII Learning Flow</a></h3>
      <p>A hands-on repository documenting digital-design fundamentals and exposure to synthesis and physical-design stages.</p>
      <p><sub>RTL · Synthesis · Physical-design flow</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/icy-chidam/CPU_with_7x5_Memory">CPU with 7×5 Memory</a></h3>
      <p>A foundational digital-system project combining a simple ALU, memory operations, and a seven-segment display interface.</p>
      <p><sub>Digital logic · ALU · Memory</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/icy-chidam/Security_System">Digital Security System</a></h3>
      <p>A password-comparison circuit built from combinational logic, with Verilog RTL, a testbench, and simulation-oriented project files.</p>
      <p><sub>Verilog · Logic design · Simulation</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/icy-chidam">Explore all repositories →</a></h3>
      <p>Browse the rest of my GitHub for experiments, coursework, implementation notes, and evolving hardware projects.</p>
      <p><sub>Open-source learning · Prototyping · Documentation</sub></p>
    </td>
  </tr>
</table>

## Selected Engineering Work

These projects represent broader team, research, and implementation work; some may not have a public code repository linked here yet.

### Radar-Based Proximity Warning System — SHAKTI / DIR-V

A team-built proximity-warning demonstrator combining mmWave radar sensing, FPGA logic, and a SHAKTI-based system. The system explores zone-aware, speed-aware response logic with on-device visual/audible alerts and event logging. The project was developed as part of the C2S / MeitY Digital India RISC-V (DIR-V) Grand Challenge.

### Spiking Neural Network ASIC Prototype

An RTL-to-GDSII exploration of a compact leaky-integrate-and-fire network, with a small hidden layer, configurable weights, an LFSR-based stochastic input encoder, alternative multiply-accumulate approaches, and activity-aware control/clock-gating ideas in a Sky130/OpenLane flow.

### Drift-Sense — Wafer-Inspection Navigation Error Recovery

A semiconductor-equipment concept focused on detecting and recovering from navigation/localization drift in wafer-inspection workflows. The team project was selected as a finalist in the SEMICON 2026 / i4C hackathon.

## Current Learning Priorities

- Strengthening SystemVerilog testbench design and structured RTL verification
- Improving timing-constraint awareness and synthesis/implementation analysis
- Building reusable, well-documented RTL IP with clear interfaces and test plans
- Exploring efficient digital architectures for secure and resource-constrained hardware

## Connect

I’m interested in connecting with engineers, researchers, and teams working in **RTL design, FPGA development, digital ASIC design, physical design, and hardware security**.

- **GitHub:** [@icy-chidam](https://github.com/icy-chidam)
- **LinkedIn:** [Chidambaresh N](https://www.linkedin.com/in/chidambareshn/)

---

<div align="center">
  <sub>Build carefully. Verify rigorously. Understand the silicon.</sub>
</div>
