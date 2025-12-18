# Simulation Model – Structure and Deployment

---

## 📋 Overview

This chapter describes the structure of the simulation model, the file formats used, and the possibilities and limitations of usage. The focus is on practical classification in the project context.

---

## 🛠️ Model Creation

### Software Used

**Siemens Plant Simulation** (Student Version)

Siemens Plant Simulation is a discrete event simulation software for analysis, visualization, and optimization of production processes, material flow, and logistics operations.

**Programming Language:** SimTalk (object-oriented)

### Modeling Approach

The model was created with the following objectives:

- **Representation of product and process assumptions:** Implementation of processes defined in [03_product-and-process](./03_product-and-process.md)
- **Alignment with early planning phase:** Focus on rough layout planning and capacity estimation
- **Experimentation capability:** Enable scenario comparisons
- **Scenario comparability:** Consistent model structure for reproducible results

### Technical Specification

- **Object count:** Below the permitted limit of 80 objects (student version)
- **Advantage:** Enables opening, execution, and saving without license violation

---

## 💾 Model Storage and File Formats

### Provided Formats in Git Repository

The model is provided in three different formats:

| Format | Description | Purpose |
|--------|-------------|---------|
| **.spp** | Native Plant Simulation model | Further editing and customization |
| **.psfm** | Plant Simulation Format for Models | Structured storage and versioning |
| **.exe** | Executable version | Usage without Plant Simulation installation |

### Storage Structure

The deliberately separated storage of formats enables:

- Flexible addition or removal of individual formats
- No change to project structure with format updates
- Clear separation between development and usage formats

---

## 🚀 Using the Model

### Option 1: Usage with Siemens Plant Simulation

**Requirements:**
- Siemens Plant Simulation version V2404 or higher
- Student or full version

**Capabilities:**
- Open and edit .spp or .psfm files
- Adjust parameters and process settings
- Conduct simulation experiments
- Save and evaluate simulation results
- Access to all interaction and customization options

**Recommended for:**
- Detailed analysis and evaluation
- Model customization
- Systematic experiments

### Option 2: Usage via Executable Version (.exe)

**Requirements:**
- No Plant Simulation installation required

**Capabilities:**
- Direct simulation start
- Interaction with predefined parameters
- Simulation execution from user perspective
- Low-threshold access

**Limitations:**
- **No saving** of simulation results possible
- Customization options limited to intended interactions
- Primarily for demonstration, interaction, and model understanding

**Recommended for:**
- First steps and getting to know the model
- Demonstration in teaching sessions
- Quick start without software installation

---

## ⚠️ Limitations of Executable Version

The .exe version is **NOT suitable** for:

- Systematic evaluation of simulation results
- Saving experiments
- Detailed analysis of key performance indicators
- Modification of model structure

**For advanced analysis, customization, or documentation, Siemens Plant Simulation is required.**

---

## 📄 License and Usage Notice

### License Type

**Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)**

### Permitted Use

- Research
- Education
- Self-directed training

### Prohibited Use

- Industrial or commercial use
- Direct modification for integration into external research questions or projects without consent

### Required Permission

For use outside permitted areas, **consent from the model creators** is required.

---

## 🔧 Technical Details

### Simulation Type

**Discrete Event Simulation (DES)**

The simulation models the system as a sequence of discrete events. The model state changes only at specific time points (e.g., process start, process end, disruption occurrence).

### Model Components

- **Processes (Machines):** Represent the six production processes
- **Material Flow (Connectors):** Connections between processes
- **Source:** Generation of products
- **Drain:** Collection of completed products
- **Control Logic (SimTalk):** Parameterization and experiment control

### Visualization

- **2D View:** Schematic representation of process arrangement
- **3D View:** Visualization in IFC factory layout (optional)

---

**Further Information:**
- [03_product-and-process](./03_product-and-process.md) – Product type and production processes
- [05_user-guide](./05_user-guide.md) – Simulation guide
- [Glossary](./glossary.md) – Technical terms

 
**Date:** December 2025

