# Product and Production Processes

---

## 📋 Overview

This chapter describes the product under consideration and the underlying production processes of the Santa Factory project. It transparently presents the product and process assumptions underlying the simulation model and how they are represented in abstracted form.

---

## 🔄 Process Understanding in the Project

### Definition of "Process"

In the Santa Factory project, the term **process** is used exclusively in the context of **discrete event simulation (DES)**.

**A process represents:**
- A value-adding processing step to modify the product within manufacturing
- A modeled processing element that temporally influences throughput
- A contribution to system dynamics

### Characteristics of Process Modeling

**Included:**
- Abstracted model objects with defined temporal and logical behavior
- Realistic representations of equipment logic
- Temporal influence on product throughput

**NOT included:**
- Area-based modeling of workstations
- Material provision areas
- Organizational units
- Spatial aspects at process level

**Classification:** The processes are assigned to the first stage of **rough layout planning**.

---

## ⚙️ Production Processes

### Sequence of Production Processes

The product passes through a **fixed, linear process chain**. All products follow the same sequence:

1. **Programming_P1** – Digital initialization and parameterization
2. **Pressing_P2** – Physical base manufacturing of product bodies
3. **Modelling_Design_P3** – Creative individualization
4. **Testing_P4** – Quality control and approval
5. **AI_Initialisation_P5** – Initialization of individual AI
6. **Packing_Sack_P6** – Packaging and scaling of gifts

**Note:** Branches, loops, or parallel process paths are not represented.

---

## 📊 Process Parameters

### Overview of Used Parameters

Each process is characterized by the following parameters:

| Parameter (German) | Parameter (English) | Meaning |
|-------------------|---------------------|---------|
| **Prozesszeit** | proc_time | Time required for a product to pass through a process |
| **Mittlere Reparaturzeit** | MTTR | Average duration of a disruption or interruption |
| **Verfügbarkeit** | Availability | Proportion of time in which a process is operational |
| **Positionsparameter** | Position Infeed, Outfeed, Z | Spatial location of the process (geometric only) |

### Process Time (proc_time)

**Definition:** Time required for a product to pass through a process.

**Significance:**
- Determines theoretical throughput
- Central to capacity analysis
- Direct impact on production speed

**Formula:** `Throughput = 1 / Process Time`

### Mean Time To Repair (MTTR)

**Definition:** Average duration of a disruption or interruption.

**Significance:**
- Represents impact of unplanned downtimes
- No modeling of specific failure causes
- Aggregated representation of downtime

**Formula:** `MTTR = Total duration of all repairs / Number of repairs`

### Availability

**Definition:** Proportion of time in which a process is operational.

**Significance:**
- Represents planned and unplanned downtimes in aggregated form
- Direct impact on effective capacity
- Component of Overall Equipment Effectiveness (OEE)

**Formula:** `Availability = Operating time / Planned production time`

### Position Parameters

**Definition:** Define the spatial location of the process (Infeed, Outfeed, Z-coordinate).

**Significance:**
- Serve exclusively for geometric classification
- **No influence** on logical or temporal behavior
- Enable visualization in 3D model

---

## 🎁 Product Description

### The AI-based Toy

The product is a **fictional AI-based toy** that is to be produced in large quantities shortly before Christmas.

**Properties:**
- Passes through all six production processes sequentially
- No product variants in the model
- Uniform process times for all units

**Abstraction:** The product is modeled as a generic object without specific physical or technical details.

---

## 📈 Process Parameter Table

### Example Parameter Values

| Process | proc_time (min) | MTTR (min) | Availability (%) |
|---------|-----------------|------------|------------------|
| Programming_P1 | 2.0 | 15 | 95 |
| Pressing_P2 | 3.5 | 20 | 90 |
| Modelling_Design_P3 | 4.0 | 18 | 92 |
| Testing_P4 | 2.5 | 12 | 96 |
| AI_Initialisation_P5 | 5.0 | 25 | 88 |
| Packing_Sack_P6 | 1.5 | 10 | 98 |

**Note:** These values are exemplary and can be adjusted in the simulation model.

---

## ⚠️ Scope Limitations

### What the Model Does NOT Include

- **Area Requirements:** No modeling of workstation or storage areas
- **Material Provision:** No detailed representation of material flows between processes
- **Production Program Planning:** No consideration of lot sizes or sequence planning
- **Production Control:** No representation of control logic or priority rules

**Rationale:** These aspects are not required for the early planning phase (Planning Phases 0-1) and would disproportionately increase modeling effort.

---

## ✅ Summary

The production processes of the Santa Factory project are deliberately abstracted and reduced to essential parameters:

- **Process Time:** Determines throughput
- **MTTR:** Represents disruptions
- **Availability:** Accounts for downtimes

This abstraction corresponds to the character of early factory planning and enables focused analysis of capacity and system behavior.

---

**Further Information:**
- [02_factory-planning](./02_factory-planning.md) – Classification in factory planning
- [04_model-and-simulation](./04_model-and-simulation.md) – Simulation model structure
- [Glossary](./glossary.md) – Technical terms

  
**Date:** December 2025
