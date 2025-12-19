# User Guide – Santa Factory Simulation

---

## 📋 Overview

This guide supports the practical application of the Santa Factory Simulation. It describes step-by-step the model start, configuration, and execution of simulations.

**Focus:** Practical use from user perspective (no theoretical background on factory planning)

---

## 🔑 Prerequisites and Getting Started

### Option 1: Usage with Plant Simulation

**Required:**
- Siemens Plant Simulation version V2404 or higher
- Student or full version

**Available:**
- All interaction and customization options
- Save changes and simulation results
- Detailed evaluation and analysis

**Recommended for:** Systematic experiments and detailed analyses

### Option 2: Usage via Executable Version (.exe)

**Required:**
- No Plant Simulation installation

**Available:**
- Direct entry into simulation
- Interaction with predefined parameters

**Limitations:**
- Customization options limited to intended interactions
- **No saving** of simulation results possible

**Recommended for:** First steps and demonstration

---

## 👤 User Role

You assume the role of a **planner** who supports Santa Claus in decision-making.

### Task

Investigate to what extent the targeted production quantity for the new product can be achieved under given constraints.

### Scenario

Santa Claus is planning the production of a new AI-based toy shortly before Christmas. You should assess whether the target production quantity can be realized with the existing factory.

---

## ⚙️ Configuration Options

### What You Can Influence

- **Set production target quantity:** Percentage selection based on worldwide number of children
- **Configure number and position of production facilities:** Placement within factory layout
- **Adjust selected process parameters:** Process time, MTTR, availability
- **Conduct multiple simulation runs for comparison:** Scenario comparison

### What Is Fixed

- **Factory layout:** Spatial structure of the factory (IFC model)
- **Sequence of production processes:** Linear process chain (P1 → P2 → P3 → P4 → P5 → P6)
- **Basic process logic:** Discrete event simulation with defined parameters
- **Product representation as product type:** Generic AI-based toy

---

## 📈 Step 1: Setting Production Target Quantity

### Definition

The production target quantity is set as a **percentage selection**.

**Reference:** Worldwide number of children who should receive a gift

### Function

Defines the targeted production quantity for the considered period.

### Effect

- **Higher target quantities:** Increase production capacity requirements
- **Bottlenecks:** Become more visible with higher target quantities
- **Scenario comparison:** Enables evaluation of different production targets

**Example:**
- 10% = 200,000 units
- 50% = 1,000,000 units
- 100% = 2,000,000 units

---

## 🏭 Step 2: Configuration of Production Processes

### Selection and Placement of Facilities

**Facilities represent production processes:**

1. **Programming_P1** – Digital initialization
2. **Pressing_P2** – Physical base manufacturing
3. **Modelling_Design_P3** – Creative individualization
4. **Testing_P4** – Quality control
5. **AI_Initialisation_P5** – AI initialization
6. **Packing_Sack_P6** – Packaging

### Placement

- Placement within the predefined factory layout possible
- **Important:** Placement influences spatial structure but has **no direct influence** on the logical sequence of processes
- Process sequence is fixed (P1 → P2 → P3 → P4 → P5 → P6)

### Number of Facilities

- You can set the **number of facilities per process**
- Multiple facilities of the same process type increase capacity
- **Example:** 2x Programming_P1 doubles capacity for this process

---



## 🚀 Step 3: Running the Simulation

### Starting the Simulation

1. **Open model** (Plant Simulation or .exe)
2. **Set parameters** (target quantity, facility count, process parameters)
3. **Start simulation** (Start button)
4. **Observe simulation** (visualization of material flow)

### Simulation Duration

- **Simulation time:** Defined period (e.g., 30 days)
- **Computation time:** Depends on model complexity (few seconds to minutes)

### Results

**Available Key Performance Indicators:**
- **Produced Quantity:** Number of completed products
- **Target Achievement:** Percentage achievement of target production quantity
- **Throughput Time:** Average time from process start to completion
- **Utilization:** Utilization of individual processes
- **Bottlenecks:** Identification of bottlenecks

---

## 📊 Step 4: Evaluation and Scenario Comparison

### Evaluating Results

**Questions for Assessment:**
- Was the target production quantity achieved?
- Which processes are bottlenecks?
- How high is facility utilization? 


**Comparison:**
- Which scenario is realistic?
- What measures are required to achieve the target quantity?
- Where are investments in additional capacity worthwhile?


---

## ✅ Summary

The Santa Factory Simulation enables:

- **Assessment of production capacity** 
- **Identification of bottlenecks** in the process chain
- **Scenario comparison** for decision support
- **Experimentation** with different configurations

**Next Steps:**
- Conduct your first experiment
- Compare different scenarios
- Document your findings

---

**Further Information:**
- [03_product-and-process](./03_product-and-process.md) – Product type and production processes
- [04_model-and-simulation](./04_model-and-simulation.md) – Simulation model structure
- [Glossary](./glossary.md) – Technical terms

 
**Date:** December 2025
