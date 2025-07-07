# 🧠 Projects by Hossain

A personal collection of software experiments, logic simulators, low-level libraries, and tools. Many of these came from curiosity, late-night inspiration, or the desire to deeply understand what’s under the hood.

---

### 📌 Notes

- Most of these were solo builds, created out of genuine curiosity and love for low-level systems.
- Some are academic or exploratory — others were made to solve real problems.
- I’m happy to revisit, improve, or collaborate on any of them.

---

> _“Build to understand. Share to inspire.”_

For more recent projects and tools, check the main [README.md](./README.md).

---

## 🧩 Systems & Simulation

### 🔢 [CordicSim](../../../CordicSim)
Full-mode CORDIC simulator using fixed-point arithmetic.  
Built to test trigonometric and hyperbolic operations in Q-format arithmetic.

### 💡 [CordicV](../../../CordicV)
A Verilog implementation of the CORDIC algorithm, with pipelined and shared stage versions.  
Great for FPGA designs or anyone learning about hardware-efficient math computation.

### 🧮 [FixedSim](../../../FixedSim)
C++ library for simulating Q<m,n> fixed-point arithmetic.  
Designed for precision-critical digital logic simulations and embedded applications.

### ⚙️ [MipSim](../../../MipSim)
A simple **real-time**, **gate-level**, **multi-cycle** MIPS **pipeline emulator**.  
Built to study how pipelining really works — instruction by instruction, cycle by cycle.
Useful for understanding pipelining, hazards, and instruction execution at the hardware level.

---

## 🛠 Hardware Logic & RTL

### 🧾 [SimpleMachine](../../../SimpleMachine)
A Verilog-based abstract machine that executes basic operations in internal registers.  
Excellent for experimenting with state transitions and control logic.

### 🧰 [SimKT](../../../SimKT)
Real-time logic gate simulator written in Kotlin for the JVM.  
An interactive way to visualize how gates behave and interact in real-time systems.

### ➕ [MathPP](../../../MathPP)
Simulates mathematical operations at a logical gate level in C++.  
Useful for learning how math is computed at the hardware logic level.

---

## 🔬 Low-Level & Binary Systems

### 📦 [Strukt.js](../../../Strukt.js)
A compact JavaScript library for working with C-like struct layouts and memory views.  
Enables easy binary parsing and memory mapping inside JS apps.

### 📁 [BinaryDatabase](../../../BinaryDatabase)
A lightweight, portable database engine in C++.  
Simple binary format, ideal for embedded or offline data storage.

---

## 💻 Web, Layout & UI Experiments

### 📐 [LayoutJS](../../../LayoutJS)
A collection of native Web Components and layout primitives.  
Provides a basic, modern layout system with **vanilla CSS** and no dependencies.

### 🔄 [ObservableJS](../../../ObservableJS)
Tiny and efficient **observable values** (signals) in plain JavaScript.  
Inspired by reactive programming patterns — no frameworks, just logic.

---

## 🎮 Game & Assembly

### 🐍 [Snake4W](../../../Snake4W)
A classic Snake game implemented for the [Wasm4](https://wasm4.org/) fantasy console.  
Written for the web in ultra-low-level WASM environments.

### 🎹 [Pianism](../../../Pianism)
A minimalist piano app written in bare x86 assembly for Windows.  
No libraries. No frameworks. Just raw assembly and creativity.

---

## ➗ Math & Utility Tools

### 🧠 [ComplexMachine](../../../ComplexMachine)
A set of tools and calculators for complex numbers — from Bash-based CLI calculators to polynomial and series solvers — all in C++.
