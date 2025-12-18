# 🎅 Santa Factory Planning Digital Twin

**Early-stage factory planning digital twin using Siemens Plant Simulation to explore production capacity in a fictional Santa Factory scenario.**

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![Plant Simulation](https://img.shields.io/badge/Plant%20Simulation-V2404-blue)](https://www.plm.automation.siemens.com/plant-simulation)

---

## 📋 Overview

The **Santa Factory Planning Digital Twin** is an experimental simulation project for early-stage factory planning based on a fictional "Santa Factory" scenario. The project compares static production estimations with dynamic **discrete event simulation (DES)** and examines production capacity, process structures, and system behavior under uncertainty.

This project demonstrates how simulation can support decision-making in the early planning phases (VDI 5200 Phases 0-1) of factory planning.

---

## 🎯 Key Features

- **Discrete Event Simulation** using Siemens Plant Simulation V2404
- **Brownfield planning** scenario with existing factory layout (IFC model)
- **Six production processes** with configurable parameters
- **Multiple usage options**: Native .spp/.psfm files and standalone .exe
- **Educational focus**: Research, teaching, and self-directed learning
- **BIM integration**: LOD 100 / LOI 100 information levels

---

## 🚀 Quick Start

### Option 1: With Siemens Plant Simulation (Recommended)

1. Install [Siemens Plant Simulation](https://www.plm.automation.siemens.com/plant-simulation) V2404 or higher (Student or Full version)
2. Open `simulation/santa_factory.spp` or `simulation/santa_factory.psfm`
3. Configure parameters and run simulation
4. Analyze results

### Option 2: Standalone Executable

1. Navigate to `simulation/`
2. Double-click `santa_factory.exe`
3. Interact with predefined parameters
4. ⚠️ **Note:** Results cannot be saved in this mode

For detailed instructions, see the [User Guide](docs/05_user-guide.md).

---

## 📂 Repository Structure

```
santa-factory-planning-digital-twin/
├── README.md                    # This file
├── LICENSE                      # CC BY-NC 4.0 license
├── docs/                        # Documentation
│   ├── 01_project-overview.md   # Project context and objectives
│   ├── 02_factory-planning.md   # Factory planning classification
│   ├── 03_product-and-process.md# Product and process description
│   ├── 04_model-and-simulation.md# Simulation model details
│   ├── 05_user-guide.md         # Step-by-step usage guide
│   └── glossary.md              # Technical terms (DE/EN)
├── simulation/                  # Simulation models
│   ├── README.md                # Simulation quick start
│   ├── *.spp / *.psfm          # Plant Simulation models
│   └── *.exe                    # Executable version
└── assets/                      # Images, diagrams, IFC models
    ├── ifc/                     # Factory layout (IFC)
    └── images/                  # Screenshots and diagrams
```

---

## 📚 Documentation

| Document | Description |
|----------|-------------|
| **[Project Overview](docs/01_project-overview.md)** | Project context, objectives, and scenario |
| **[Factory Planning](docs/02_factory-planning.md)** | VDI 5200/3633 classification, BIM concepts |
| **[Product & Process](docs/03_product-and-process.md)** | Production processes and parameters |
| **[Model & Simulation](docs/04_model-and-simulation.md)** | Model structure, file formats, technical details |
| **[User Guide](docs/05_user-guide.md)** | Step-by-step instructions for using the simulation |
| **[Glossary](docs/glossary.md)** | Technical terms in German and English |

---

## 🎓 Learning Objectives

This project is designed for:

- **Students and educators** in factory planning, production, and simulation
- **Individuals interested** in discrete event simulation
- **Simulation experts** for model analysis and extension

### What You'll Learn

- Early-stage factory planning methodology (VDI 5200)
- Discrete event simulation principles (VDI 3633)
- Capacity planning under dynamic conditions
- BIM concepts (LOIN, LOD, LOI) in factory planning
- Scenario comparison for decision support

---

## ⚙️ Technical Specifications

- **Software:** Siemens Plant Simulation V2404 (Student Version compatible)
- **Simulation Type:** Discrete Event Simulation (DES)
- **Programming Language:** SimTalk (object-oriented)
- **Object Count:** < 80 objects (within student version limits)
- **Planning Phase:** VDI 5200 Phases 0-1
- **Information Level:** LOD 100 / LOI 100

---

## 📄 License

This project is licensed under **CC BY-NC 4.0** (Creative Commons Attribution-NonCommercial 4.0 International).

### ✅ Permitted Use
- Research
- Education  
- Self-directed training

### ❌ Prohibited Use
- Industrial or commercial applications
- Modification without creator consent

For full license details, see [LICENSE](LICENSE).

### Citation

When using this project, please cite:

```
Dilg, A., & Rube, N. (2025). Santa Factory Planning Digital Twin. 
GitHub repository. https://github.com/kikki/santa-factory-planning-digital-twin
```

---

## ✍️ Authors

**Project Period:** November 25, 2025 – December 20, 2025

**Creators:**
- Alex Dilg ([@AlexD_SimPlan](https://community.sw.siemens.com/s/profile/0054O000007xmBsQAI))
- Natalja Rube ([@nadin1223](https://community.sw.siemens.com/s/profile/0054O000007xnyH))

**Context:** Research, education, and self-directed training (no commercial purpose)

---

## 🔗 Resources

- [VDI 5200](https://www.vdi.de/mitgliedschaft/vdi-richtlinien/details/vdi-5200-blatt-1-fabrikplanung-planungsvorgehen) – Factory Planning Guideline
- [VDI 3633](https://www.vdi.de/mitgliedschaft/vdi-richtlinien/details/vdi-3633-blatt-1-simulation-von-logistik-materialfluss-und-produktionssystemen-grundlagen) – Simulation Guideline  
- [Siemens Plant Simulation](https://resources.sw.siemens.com/de-DE/download-tecnomatix-plant-simulation-student-software/) – Simulation Software Studentenversion
- [buildingSMART](https://www.buildingsmart.org/standards/bsi-standards/industry-foundation-classes/) – IFC Standards

---

## 🤝 Contributing

This is an educational project. For questions, feedback, or collaboration inquiries, please contact the authors via their Siemens Community profiles.

---

 
**Date:** December 2025  
**License:** CC BY-NC 4.0
