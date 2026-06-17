# VLSI Design Internship – IHP 130nm Technology

## Overview

This repository presents the digital and analog IC design experiments completed during the **VLSI Design Internship** using the **IHP Open PDK (130nm Technology)**. The work covers the complete custom IC design flow including schematic capture, circuit simulation, layout design, LVS verification, and performance analysis.

The project demonstrates practical implementation of CMOS logic gates, sequential circuits, and analog building blocks using industry-standard open-source EDA tools.

---

## Technology Stack

| Category           | Tool               |
| ------------------ | ------------------ |
| Process Technology | IHP Open PDK 130nm |
| Schematic Design   | Xschem             |
| Circuit Simulation | NGSpice            |
| Layout Design      | Magic VLSI         |
| LVS Verification   | Netgen             |

---

## Repository Structure

```text
images/
├── inverter/
├── and_gate/
├── nand_gate/
├── nor_gate/
├── or_gate/
├── d_flipflop/
├── shift_register/
└── bandgap_reference/
```

---

# Digital Circuit Design

## CMOS Inverter

The CMOS inverter is the fundamental building block of digital integrated circuits. It consists of a complementary PMOS-NMOS pair providing low static power consumption and full voltage swing.

### Schematic

![Inverter Schematic](images/inverter/inverter_sch.png)

### Layout

![Inverter Layout](images/inverter/inverter_magic.png)

### DC Transfer Characteristics

![Inverter DC Analysis](images/inverter/inverter_dc_analysis.png)

### AC Analysis

![Inverter AC Analysis](images/inverter/inverter_ac_analysis.png)

### LVS Verification

![Inverter LVS](images/inverter/inverter_lvs_out.png)

---

## CMOS NAND Gate

The NAND gate was designed using complementary CMOS logic and verified through schematic simulation and layout implementation.

### Schematic

![NAND Schematic](images/nand_gate/nand_gate_sch.png)

### Layout

![NAND Layout](images/nand_gate/nand_gate_magic.png)

### Simulation Results

![NAND Analysis](images/nand_gate/nand_gate_dc_analysis.png)

---

## CMOS NOR Gate

The NOR gate was implemented and validated using the IHP 130nm process design kit.

### Schematic

![NOR Schematic](images/nor_gate/nor_gate_sch.png)

### Layout

![NOR Layout](images/nor_gate/nor_gate_magic.png)

### Simulation Results

![NOR Analysis](images/nor_gate/nor_gate_dc_analysis.png)

---

## CMOS AND Gate

The AND gate was realized using NAND logic followed by inversion.

### Schematic

![AND Schematic](images/and_gate/and_gate_sch.png)

### Simulation Results

![AND Analysis](images/and_gate/and_gate_dc_analysis.png)

---

## CMOS OR Gate

The OR gate was implemented using NOR logic followed by inversion.

### Schematic

![OR Schematic](images/or_gate/or_gate_sch.png)

### Simulation Results

![OR Analysis](images/or_gate/or_gate_dc_analysis.png)

---

# Sequential Circuit Design

## D Flip-Flop

The D Flip-Flop serves as the fundamental storage element in synchronous digital systems.

### Schematic

![DFF Schematic](images/d_flipflop/d_ff_sch.png)

### Layout

![DFF Layout](images/d_flipflop/d_ff.png)

### Analysis

![DFF Analysis](images/d_flipflop/d_ff_analysis.png)

---

## 4-Bit Shift Register

A 4-bit shift register was implemented using cascaded D Flip-Flops for serial data storage and transfer.

### Schematic

![Shift Register Schematic](images/shift_register/shift_reg_4_bit_sch.png)

### Layout

![Shift Register Layout](images/shift_register/shif_reg_4_bit.png)

### Simulation

![Shift Register Analysis](images/shift_register/shift_reg_4_bit_analysis.png)

---

# Analog Circuit Design

## Bandgap Reference Circuit

The Bandgap Reference (BGR) circuit generates a temperature-stable reference voltage independent of supply and temperature variations.

### Schematic

![BGR Schematic](images/bandgap_reference/bgr_sch.png)

### Layout

![BGR Layout](images/bandgap_reference/bgr_magic.png)

### DC Analysis

![BGR DC Analysis](images/bandgap_reference/bgr_dc_analysis.png)

### Current Consumption

![Current Consumption](images/bandgap_reference/bgr_current_consumption.png)

### Startup Analysis

![Startup Analysis](images/bandgap_reference/bgr_startup_time.png)

### Temperature Analysis

![Temperature Analysis](images/bandgap_reference/bgr_temp_diff.png)

### LVS Verification

![BGR LVS](images/bandgap_reference/bgr_lvs_out.png)

---

# Key Learning Outcomes

* CMOS logic gate design and verification
* Analog circuit design using IHP Open PDK
* Custom layout implementation using Magic VLSI
* LVS verification using Netgen
* DC, AC, and transient simulation using NGSpice
* Digital sequential circuit implementation
* Industry-standard open-source VLSI design flow

---

# Author

**Nandakishor P B**
B.Tech Electronics and Communication Engineering
IIIT Kottayam

**VLSI Design Internship**
Digital University Kerala
