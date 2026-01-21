# LTspice Simulation: Simple Resistive Circuit

## Project Overview
This repository contains an LTspice simulation of a basic resistive voltage divider circuit - a foundational exercise in circuit analysis and simulation.

## Circuit Description
A simple **two-resistor voltage divider** powered by a DC voltage source:
- **Input Voltage (V1)**: 10 V DC
- **Resistors**:
  - R₁ = 1 kΩ
  - R₂ = 1 kΩ
- **Output**: Voltage at the node between R₁ and R₂ (labeled "out")

### Schematic Representation


**Expected output voltage** (theoretical calculation):
\[
V_{out} = V_{in} \times \frac{R_2}{R_1 + R_2} = 10 \times \frac{1k}{1k + 1k} = 5.0 \text{ V}
\]

## Files in This Repository
| File | Description |
|------|-------------|
| [`Chigozirim's First Resistive Circuit.asc`](Chigozirim's%20First%20Resistive%20Circuit.asc) | Main LTspice schematic file |
| `README.md` | This documentation file |

## How to Run the Simulation
1. **Open LTspice** (version XVII or later recommended)
2. **Open** the `.asc` file from this repository
3. **Run the simulation**:
   - Click the **"Run"** icon (or press `Ctrl+R`)
   - This performs a DC operating point analysis automatically
4. **View results**:
   - The output voltage is available at the node labeled **"out"**
   - Place a voltage probe on the "out" node to confirm V_out = 5.0 V

## Simulation Results
- **Output voltage**: 5.0 V (matches theoretical calculation)
- **Current through circuit**: 5 mA
- **Power dissipation per resistor**: 25 mW

## Key Parameters
| Parameter | Value | Unit |
|-----------|-------|------|
| Input Voltage (V1) | 10 | V |
| Resistor R1 | 1 | kΩ |
| Resistor R2 | 1 | kΩ |
| Output Voltage | 5 | V |
| Circuit Current | 5 | mA |

## Learning Objectives
- Introduction to LTspice schematic capture
- Basic DC circuit analysis principles
- Voltage divider circuit verification
- Using node labels for measurement points
- Comparing simulation results with theoretical calculations

## Author
- **Chigozirim** - Electrical/Electronics Engineering student
- **Course**: Introductory Circuit Analysis
- **Simulation Date**: 2024

## Requirements
- **LTspice** (free download from [Analog Devices](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html))
- No additional libraries required

## Notes
- This is a basic DC analysis simulation
- The schematic includes the comment: "This Simple Resistive Circuit"
- All components use default LTspice models
- Ground (0V reference) is properly connected

## Future Enhancements
Potential improvements for extended learning:
1. Add transient analysis with time-varying input
2. Include frequency response analysis
3. Parameter sweep to analyze different resistor values
4. Temperature analysis for resistor behavior
5. Add measurement plots and output files

---
**Note**: This simulation demonstrates fundamental circuit theory principles using industry-standard simulation tools.
