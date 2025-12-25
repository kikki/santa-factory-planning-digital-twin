# Santa Factory Planning Digital Twin

Welcome to the **Santa Factory Planning Digital Twin**! An experimental simulation project for early-stage factory planning based on a fictional Santa Factory scenario.

---

## 📋 Project Overview

The **Santa Factory Planning Digital Twin** is an experimental simulation project for early-stage factory planning based on a fictional "Santa Factory" scenario. The project compares static production estimations with dynamic discrete event simulation (DES) and examines production capacity, process structures, and system behavior under uncertainty.

### Core Objectives

- Compare static production estimations with discrete event simulation
- Examine production capacity and system behavior under uncertainty
- Align with planning phases 0 and 1 of factory planning according to VDI 5200
- Provide an educational and research project for factory planning and simulation

### Scenario

Santa Claus is planning to introduce a new AI-based toy shortly before Christmas. Based on an existing factory layout (brownfield planning), the project investigates to what extent the targeted production quantity can be achieved under given constraints.

---

## 🗂️ Repository Structure

The project is modularly structured and organized into the following areas:

| Area | Content |
|------|---------|
| **[02_factory-planning](./02_factory-planning.md)** | Classification in factory planning, planning phase, methodological framework (VDI 5200, VDI 3633, LOIN/LOD/LOI) |
| **[03_product-and-process](./03_product-and-process.md)** | Product type, production processes, process parameters |
| **[04_model-and-simulation](./04_model-and-simulation.md)** | Simulation model structure, software, file formats, usage options |
| **[05_user-guide](./05_user-guide.md)** | Simulation guide, scenario configuration, simulation runs |
| **[glossary](./glossary.md)** | Glossary of all technical terms (German/English) |

---

## 👥 Target Audience

This project is aimed at:

- **Students and educators** in factory planning, production, and simulation
- **Individuals interested** in discrete event simulation
- **Simulation experts** for analysis and model extension

**Excluded:** Industrial or commercial applications

---

## 🚀 Entry Points

Depending on your interest, we recommend the following entry points:

- **Technical Classification:** [02_factory-planning](./02_factory-planning.md)
- **Content Details:** [03_product-and-process](./03_product-and-process.md)
- **Technical Implementation:** [04_model-and-simulation](./04_model-and-simulation.md)
- **Practical Application:** [05_user-guide](./05_user-guide.md)

---

## 📐 Methodological Framework

### Factory Planning according to VDI 5200

The project is aligned with the early planning phases of factory planning:

- **Planning Phase 0 – Goal Definition:** Clarification of objectives and definition of planning goals
- **Planning Phase 1 – Baseline Assessment:** Estimation of production program and required production processes

### Simulation according to VDI 3633

Discrete event simulation enables the analysis of dynamic system effects that cannot be captured in static calculations. The model represents process structures, capacity relationships, and system behavior.

### BIM Concepts (LOIN, LOD, LOI)

The project uses BIM terminology to classify information needs:

- **LOIN (Level of Information Need):** Defines the required information need
- **LOD (Level of Detail):** Geometric detail (LOD 100 – conceptual)
- **LOI (Level of Information):** Alphanumeric information (LOI 100 – basic)

---

All assets used in this study come from online resources, prepared using a classical workflow including bone-based rigging where required.

### Equipment and Characters
- Process machines
- Santa and reindeer characters with bone-based rigging

### Factory Building (IFC Model)
The factory building model was created and exported via IFC. The IFC model was directly imported with minor modifications (missing roof element and door animations). It includes:
- Standard BIM families (walls, doors, gates, windows)
- Freely available families (shelves, toilets)

### Asset Sources
- [CGTrader](https://www.cgtrader.com) – 3D models
- [Free3D](https://free3d.com) – 3D models

- [BIMobject](https://www.bimobject.com) – BIM objects and families
- [MEPcontent](https://www.mepcontent.com) – MEP families and content

---

## 📄 License and Usage

**License:** Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)

### Permitted Use

- Research
- Education
- Self-directed training

### Prohibited Use

- Industrial or commercial application
- Modification without consent of the creators

### Citation

Explicit citation of this repository is required when using this project.

---

## ✍️ Authors and Project Development

**Project Period:** November 25, 2025 – December 20, 2025

**Creators:**
- Alex Dilg ([Plant Simulation Community @AlexD_SimPlan](https://community.sw.siemens.com/s/profile/0054O000007xmBsQAI))
- Natalja Rube ([Plant Simulation Community @nadin1223](https://community.sw.siemens.com/s/profile/0054O000007xnyH))

**Context:** Research, education, and self-directed training (no commercial purpose)

---

## 🔗 Further Information

- [Glossary](./glossary.md) – All technical terms in German and English
- [VDI 5200](https://www.vdi.de) – Factory Planning Guideline
- [VDI 3633](https://www.vdi.de) – Simulation Guideline
- [Siemens Plant Simulation](https://www.plm.automation.siemens.com/plant-simulation) – Simulation Software

---

 
**Date:** December 2025  
**License:** CC BY-NC 4.0
