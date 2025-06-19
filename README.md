# 🎛️ Dual-Frequency Sine Wave Generator using Xilinx Block Memory Generator (PS + PL)

This project implements a **Dual-Frequency Sine Wave Generator** leveraging the **Block Memory Generator IP** in Xilinx Vivado. It uses both the **Processing System (PS)** and **Programmable Logic (PL)** on an FPGA SoC to generate two distinct sine wave signals based on pre-stored LUTs (Look-Up Tables) in BRAM. The output frequency can be switched dynamically based on control input from PS.

---

## 📌 Features

- 🔁 **Dual Frequency Output**: Generates two selectable sine wave frequencies.
- 💾 **Block Memory Generator**: Stores precomputed sine wave samples as LUTs.
- 🔗 **PS + PL Integration**: Zynq Processing System controls frequency switching.
- 📡 **Continuous Output**: Ideal for DAC output or digital waveform analysis.
- 🛠️ **Vivado IP Integrations**: Uses BRAM and custom logic blocks.
- 🧪 **Simulated in Vivado** with waveform validation via **XSim** or **GTKWAVE**.

---

## 🔧 Tools & Environment

- **Vivado Design Suite** (Xilinx)
- **Zynq-7000 SoC Platform** (e.g., ZCU104 / ZedBoard)
- **Block Memory Generator IP**
- **AXI Interface for PS-PL communication**
- **Vivado ISE** for simulation

---
**Block Daigram**
<p align="center">
  <img src="![Uploading Simulation Waveform - Copy.png…]()
" alt="Block Diagram" width="600"/>
</p>

---

## 📡 Simulation Waveform

<p align="center">
  <img src="images/simulation_waveform.png" alt="Simulation Waveform" width="600"/>
</p>


