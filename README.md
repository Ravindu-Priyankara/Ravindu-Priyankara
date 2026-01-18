<h1 align="center">Low‑Level Security Research & Binary Analysis</h1>

<p align="center">
  <i>“Silence. Precision. Control.”</i>
</p>

## About Me

I’m a self‑taught low‑level security researcher focused on **understanding, analyzing, and reasoning about binary behavior at the instruction level**.

My work centers on how executables actually behave at runtime — from ELF loading and control flow to stack frames, memory protections, and system calls. I study both **benign and malicious binaries** to improve analysis, debugging, and security understanding.

I care less about tools and more about **first principles**: what the CPU executes, how memory is accessed, and why programs behave the way they do.

---

## Core Focus Areas

* Reverse engineering Linux ELF binaries
* Binary instrumentation and patching for research & analysis
* Analysis of anti‑debugging and anti‑analysis techniques used in protected or malicious software
* Instruction‑level debugging with GDB and radare2
* Understanding memory protections (PIE, NX, ASLR, stack canaries)
* Control‑flow integrity and execution tracing

---

## What I Build

* Binary analysis and malware‑neutralization labs
* Control‑flow redirection and instrumentation demonstrations
* Reverse‑engineered binaries with documented behavior
* Instruction‑level debugging walkthroughs
* Educational exploit primitives to understand vulnerability mechanics
* Research notes, diagrams, and proof screenshots for clarity and reproducibility

> All projects are **educational and research‑focused**, designed to explain *how* binaries work — not to deploy malicious software.

---

## Learning Roadmap (Active)

* ✔ C fundamentals & pointers
* ✔ Stack & heap internals
* ✔ Dynamic memory & memory corruption basics
* 🔥 Reverse engineering & binary instrumentation
* 🔥 Analysis of anti‑debugging and anti‑analysis techniques
* ► Next: Advanced malware analysis → exploit development fundamentals

---

## Technical Stack (Specialized)

**Languages**

* C
* Assembly (x86‑64)
* Python

**Tools & Environments**

* GDB
* radare2
* Ghidra
* objdump
* strace
* Linux
* gcc / make

*(Pwntools used only for controlled educational experiments)*

---

## Research Philosophy

I believe strong security engineers understand systems **from the bottom up**.

Instead of relying on frameworks or automation, I focus on:

* reading raw instructions
* tracking register state
* understanding calling conventions
* following execution paths precisely

Depth, clarity, and correctness matter more than speed.

---

## Current Direction

Building a public research portfolio around:

* Binary instrumentation via control‑flow redirection
* ELF analysis and execution tracing
* Defensive understanding of techniques used by protected and malicious binaries

---
