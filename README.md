# RTL Forge — AI-Assisted RTL Development

RTL Forge is a hardware-aware RTL copilot designed to accelerate Verilog design using a combination of AI-assisted generation and deterministic rule-based validation built with the assistance of vibe coding tools.

It allows engineers to:

* Generate synthesizable RTL from natural language
* Detect structural design errors
* Get guided fix suggestions (not blind overwrites)
* Estimate design complexity

Unlike generic AI tools, RTL Forge enforces **hardware correctness** through a custom-built rule engine that detects issues like blocking assignments, missing reset logic, latch inference, FSM errors, and more.

---

## ⚙️ Core Features

* Natural Language → Verilog Generation
* RTL Error Detection (8-rule engine)
* Suggested Fix Snippets
* Complexity Estimation (Low → Very High)
* Dual Mode: Detect & Generate

---

## 🧠 Architecture

User Input → Prompt Engine → RTL Generator → Rule Engine → Complexity Analyzer → Output

---

## 🏗️ Tech

HTML • CSS • JavaScript • Custom Rule Engine • Verilog Templates • LLM Integration

---

## ⚠️ Note

Designed for early-stage RTL development. Final validation must be done using simulation and synthesis tools.

---

