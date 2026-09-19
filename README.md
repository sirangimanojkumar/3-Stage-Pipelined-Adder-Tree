# 3-Stage Pipelined Adder Tree

A 3-stage pipelined adder tree design, implemented and taken through the RTL-to-GDSII physical design flow.

##  Overview

This project implements an adder tree architecture with **3 pipeline stages**, designed to improve throughput by breaking the combinational adder chain into balanced, clocked stages. Pipelining reduces the critical path per stage, allowing the design to run at a higher clock frequency at the cost of added latency (in cycles).

## Repository Structure

```
3-Stage-Pipelined-Adder-Tree/
├── 3-Stage Pipelined Adder Tree/   # RTL, testbench, and design files
└── .DS_Store                       # (macOS system file — can be removed)
```

## Design Flow

This design was carried through a standard open-source physical design flow:

1. **RTL Design** - Adder tree logic described in Verilog/HDL
2. **Simulation & Verification**  - Functional verification of the pipelined datapath
3. **Synthesis** - RTL synthesized to gate-level netlist
4. **Physical Design (Place & Route)** - Using **OpenROAD** / **OpenLane**
5. **GDSII Generation** - Final layout exported as GDSII for fabrication

##  Tools Used

- Verilog / SystemVerilog (RTL)
- Open-source EDA tools (OpenROAD, OpenLane)
- Standard cell PDK (specified node Sky130)

##  Getting Started

```bash
git clone https://github.com/sirangimanojkumar/3-Stage-Pipelined-Adder-Tree.git
cd 3-Stage-Pipelined-Adder-Tree
```

*(Add simulation/build instructions here once finalized — e.g., how to run the testbench or the OpenLane flow.)*

##  Results

*(Add area, timing, and power results here once available, along with layout screenshots )*

##  License

*(Add a license if you'd like this to be open source — MIT is a common choice for hardware projects like this.)*

