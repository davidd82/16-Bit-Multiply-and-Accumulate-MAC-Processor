# 16-Bit Multiply-and-Accumulate (MAC) Processor

A custom 16-bit Multiply-and-Accumulate (MAC) processor designed and implemented in Cadence Virtuoso using transistor-level CMOS digital circuit design techniques. The project focuses on arithmetic hardware optimization, physical layout design, and VLSI verification methodologies.

---

## Project Overview

This project implements a 16-bit MAC processor capable of performing high-speed arithmetic operations commonly used in digital signal processing (DSP), machine learning accelerators, and embedded systems.

The MAC architecture was designed using:
- Radix-4 Booth Encoding
- Compressor-based arithmetic optimization
- Hierarchical digital circuit design
- CMOS transistor-level implementation

The project includes:
- Schematic design
- Physical layout creation
- DRC/LVS verification
- Timing optimization
- Transistor sizing

---

## Features

- 16-bit Multiply-and-Accumulate architecture
- Radix-4 Booth multiplication optimization
- Compressor-based reduction logic
- CMOS transistor-level circuit implementation
- Hierarchical VLSI design methodology
- Physical layout generation in Cadence Virtuoso
- DRC and LVS verification
- Timing and datapath optimization

---

## Components Designed

The following digital building blocks were designed and integrated into the MAC processor:

- D Flip-Flops (DFF)
- Radix-4 Booth Encoders
- 6-2 Compressors
- Adders
- Arithmetic datapath logic
- Sequential logic components

---

## Tools & Technologies

- Cadence Virtuoso
- CMOS Digital Circuit Design
- VLSI Layout Design
- DRC Verification
- LVS Verification

---

## Design Methodology

### 1. Schematic Design
Transistor-level schematics for arithmetic and sequential logic components were created in Cadence Virtuoso.

### 2. Arithmetic Optimization
Radix-4 Booth encoding and compressor-based reduction techniques were implemented to improve multiplication efficiency and reduce datapath complexity.

### 3. Physical Layout
Custom layouts were designed for all circuit blocks while following CMOS layout design rules and minimizing area usage.

### 4. Verification
Design Rule Check (DRC) and Layout Versus Schematic (LVS) verification were performed to validate physical layout correctness and schematic consistency.

### 5. Timing Optimization
Transistor sizing and datapath optimization techniques were applied to improve timing performance and signal reliability.

---

## Project Goals

- Understand transistor-level digital design
- Implement arithmetic optimization techniques
- Gain experience with VLSI physical layout workflows
- Practice verification methodologies used in ASIC development
- Explore datapath and timing optimization strategies

---

## Screenshots

Add screenshots of your:
- Schematic designs
- Layouts
- DRC/LVS results
- Waveforms
- MAC datapath diagrams

Example:

```md
![MAC Layout](images/mac-layout.png)
```

---

## Future Improvements

- Pipelined MAC architecture
- Power optimization techniques
- Clock tree optimization
- Timing analysis automation
- Larger datapath support (32-bit / 64-bit)
- ASIC synthesis and fabrication flow

---

## Author

David [Last Name]  
Computer Engineering & Computer Science Student at USC
