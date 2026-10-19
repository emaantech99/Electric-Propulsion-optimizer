# Electric-Propulsion-optimizer
A set of different codes used to optimize UAVs electric propulsion parameters . 

## 🎯 Objectives

- Support preliminary electric propulsion system sizing for UAVs.
- Estimate thrust and electrical power requirements.
- Evaluate motor, propeller, and battery configurations.
- Estimate energy consumption and flight endurance.
- Connect propulsion performance with aerodynamic efficiency and UAV optimization.

## ⚙️ Proposed Features

### 1. Motor Selection
Evaluate candidate electric motors using parameters such as:
- Motor KV rating
- Maximum voltage and current
- Power rating
- Efficiency characteristics
- Motor mass

### 2. Propeller Selection
Explore propeller configurations based on:
- Propeller diameter and pitch
- Rotational speed
- Thrust requirements
- Power consumption
- Propeller efficiency

### 3. Battery Sizing
Estimate battery requirements using:
- Battery voltage
- Capacity (mAh)
- Available energy (Wh)
- Discharge limits
- Battery mass

### 4. Thrust and Power Estimation
Estimate the propulsion system's thrust and power requirements under specified operating conditions.

Predictions should account for motor and propeller performance data rather than relying solely on simplified theoretical relationships.

### 5. Endurance and Range Estimation
Combine estimated electrical energy consumption with UAV performance parameters to investigate:
- Flight endurance
- Energy required for a mission
- Estimated cruise power
- Potential flight range

Actual endurance and range depend on aircraft mass, aerodynamic drag, propulsion efficiency, battery characteristics, and flight conditions.

## 🛠️ Technology Stack

Planned implementation may use:
- Python
- NumPy and Pandas
- SciPy for numerical calculations and optimization
- Matplotlib for performance visualization
- Streamlit for an interactive engineering interface

The final technology stack will reflect the libraries actually used in the implementation.

## 📥 Inputs and Outputs

**Potential inputs**
- UAV mass and geometry
- Required thrust and cruise speed
- Motor and propeller specifications
- Battery voltage and capacity
- Mission duration and flight conditions

**Potential outputs**
- Estimated thrust and power
- Candidate propulsion configurations
- Battery energy requirements
- Estimated endurance and range
- Propulsion mass and efficiency comparisons

## Engineering Limitations

This module is intended for preliminary engineering analysis. Results depend on the accuracy of component specifications, performance maps, modelling assumptions, and operating conditions.

Final propulsion selection should be validated using manufacturer data, suitable bench testing, thermal and electrical limits, and flight testing.


##  Author

Emaan Noor 
BS Aerospace Engineering  
Institute of Space Technology, Pakistan



---

*Connecting aerodynamic efficiency, electric propulsion, and intelligent UAV performance optimization.*
