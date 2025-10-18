🧠 8-Week Hardware Verification Engineer Master Plan

**(SystemVerilog + UVM + AXI + PCIe)**

---

📘 **Overview**

This 8-week program is designed to transform you from a basic verification learner into a **job-ready junior hardware verification engineer**, with strong hands-on experience in **UVM, SystemVerilog, AXI, and PCIe**.

The program simulates a **real project workflow** — from building your base UVM environment to verifying complex protocols with scoreboards, coverage, and regressions.

---

🎯 **Objectives**

By the end of this program, you will be able to:

✅ Build complete UVM verification environments from scratch
✅ Write, debug, and extend UVM components (agent, monitor, driver, scoreboard)
✅ Design and implement AXI4/AXI4-Lite and PCIe verification environments
✅ Develop constrained-random testbenches using SystemVerilog features
✅ Implement functional coverage, assertions, and regression automation
✅ Debug simulation issues systematically using logs and waveforms

---

🧭 **8-Week Learning Roadmap**

---

 🗓️ **WEEK 1 — Base UVM Environment Setup (Skeleton Creation)**

**🎯 Goal:**
Build a reusable, fully connected UVM environment that serves as your foundation for all further verification work.

**📚 Topics Covered:**

* UVM component hierarchy (Driver, Monitor, Agent, Env, Scoreboard, Test)
* Phasing mechanism (build → connect → run → report)
* Factory registration and configuration DB usage
* Virtual interfaces and connectivity
* Basic test creation and simulation flow

**🧪 Hands-on Project:**

* Create a simple DUT (like pass-through or register block)
* Build a minimal UVM testbench with all components
* Write and execute your first sequence and test
* Debug UVM reports and verify data flow through all components

---

 🗓️ **WEEK 2 — Advanced SystemVerilog for Verification**

**🎯 Goal:**
Enhance your technical depth and logic building with advanced SV concepts required for professional UVM work.

**📚 Topics Covered:**

* Constrained randomization (inline, randc, pre/post randomize)
* Advanced data types (queues, associative arrays, mailboxes, semaphores)
* Functional coverage (covergroup, cross, ignore_bins, illegal_bins)
* SystemVerilog Assertions (SVA) for protocol validation
* Multi-threaded testbench synchronization (`fork-join`, `disable fork`)

**🧪 Hands-on Project:**

* Write a random transaction generator and coverage model
* Integrate assertions for protocol checks
* Debug randomization failures and illegal bins

---

 🗓️ **WEEK 3 — UVM Deep Dive & Reusable Components**

**🎯 Goal:**
Understand UVM at a professional level and learn to create reusable, layered verification components.

**📚 Topics Covered:**

* UVM Phases (detailed flow and callbacks)
* Objection mechanism and phase control
* Sequence layering and virtual sequencers
* Factory overrides (type & instance)
* Config_db vs Resource_db usage
* Scoreboard and reference model design

**🧪 Hands-on Project:**

* Create layered sequences (random + directed)
* Build a scoreboard with transaction comparison logic
* Implement factory overrides for flexibility
* Debug multi-component UVM flows

---

 🗓️ **WEEK 4 — AXI4 & AXI4-Lite Verification (Part 1)**

**🎯 Goal:**
Learn the AXI protocol fundamentals and start building your AXI UVM environment.

**📚 Topics Covered:**

* AXI basics: channels (AW, W, B, AR, R)
* VALID/READY handshake mechanism
* Address, burst, and response types
* AXI4 vs AXI4-Lite differences
* Interface and transaction modeling

**🧪 Hands-on Project:**

* Implement `axi_if.sv` interface
* Create AXI transaction, driver, and monitor
* Build basic read/write sequences
* Validate read/write flow on a sample DUT

---

 🗓️ **WEEK 5 — AXI4 Verification (Part 2)**

**🎯 Goal:**
Complete the AXI verification environment and make it production-ready.

**📚 Topics Covered:**

* UVM Agent and Environment integration for AXI
* AXI Scoreboard for read/write response checking
* Functional coverage for burst, response, and alignment
* Protocol violation and error scenario testing

**🧪 Hands-on Project:**

* Integrate AXI agent, env, and scoreboard
* Develop and run random & directed AXI test cases
* Collect functional coverage and generate reports
* Introduce random delays and error checks

---

 🗓️ **WEEK 6 — PCIe Protocol & Transaction-Level Modeling**

**🎯 Goal:**
Understand PCIe’s architecture and build a transaction-level verification model.

**📚 Topics Covered:**

* PCIe protocol layers: Transaction, Data Link, Physical
* TLP (Transaction Layer Packet) format and fields
* Request/Completion packet mechanism
* BAR decoding and address mapping
* LTSSM (Link Training and Status State Machine) overview

**🧪 Hands-on Project:**

* Model a PCIe TLP transaction class
* Build a packet generator sequence
* Create a monitor to decode TLP headers
* Generate directed tests for MemRd/MemWr

---

 🗓️ **WEEK 7 — PCIe Verification Environment & Debugging**

**🎯 Goal:**
Develop a PCIe scoreboard and learn professional-level debugging techniques.

**📚 Topics Covered:**

* PCIe completion matching using tags
* Ordering, flow control, and credit handling
* Backpressure and timing behavior
* Reset and error injection
* Advanced debugging and log tracing

**🧪 Hands-on Project:**

* Integrate PCIe monitor and scoreboard
* Implement corner cases (CRC error, timeout)
* Perform regression runs and analyze failures
* Debug waveforms and improve environment reliability

---

 🗓️ **WEEK 8 — Integration, Regression, and Reporting**

**🎯 Goal:**
Combine all components (AXI + PCIe) into one SoC-level verification environment and automate regressions.

**📚 Topics Covered:**

* Integration of multiple agents (AXI + PCIe)
* UVM test library and test control mechanisms
* Coverage collection and merging
* Regression scripting (Makefile or Python)
* Writing vPlan and final documentation

**🧪 Hands-on Project:**

* Create top-level SoC verification environment
* Automate regression and report generation
* Merge coverage and track pass/fail metrics
* Deliver a final working verification setup

