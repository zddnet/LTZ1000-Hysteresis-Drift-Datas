# Supplementary Data for: Software-Based Thermal Hysteresis Elimination and Temperature Drift Compensation for an Oven-Controlled Precision Voltage Reference

**Authors:** Dunding Zuo

**Affiliation:** College of Mechanical and Electrical Engineering, Huangshan University, Huangshan, China

**Corresponding Author:** Dunding Zuo

---

## Overview

This repository contains the raw experimental data supporting the figures in the above manuscript. The data are provided to enhance the reproducibility of the research.

## File List

| File Name | Description | Corresponding Figure |
|-----------|-------------|----------------------|
| `Supplementary_Data_Figures_3_to_6_Hysteresis.xlsx` | Thermal hysteresis elimination experimental data (continuous power, 1.5 h power-off, 11.5 h power-off) | Figs. 3, 4, 5, 6 |
| `Supplementary_Data_Figures_7_Temperature_Drift.xlsx` | Temperature drift characteristics of the DUT with DG412 | Fig. 7 |
| `Supplementary_Data_Figures_8_Temperature_Drift.xlsx` | Temperature drift characteristics of the DUT with ADG452 | Fig. 8 |
| `Supplementary_Data_Figures_9_Temperature_Drift.xlsx` | Temperature drift characteristics after software compensation | Fig. 9 |
| `Supplementary_Data_Figures_10_11_Temperature_Drift.xlsx` | Temperature drift characteristics at 3V output | Fig. 10, 11 |
| `Supplementary_Data_Figures_12_Temperature_Drift.xlsx` | Temperature drift characteristics before software compensation at 6V output of ADR1399 | Fig. 12 |
| `Supplementary_Data_Figures_13_Temperature_Drift.xlsx` | Temperature drift characteristics after software compensation at 6V output of ADR1399 | Fig. 13 |

---

## File Descriptions

### 1. Supplementary_Data_Figures_3_to_6_Hysteresis.xlsx

This file contains the output voltage measurements during thermal hysteresis elimination experiments under three operating conditions:
  continuous power,  1.5 h power interruption, 11.5 h power interruption
	
**Columns:**
- `Time - Meas`: Elapsed date-time
- `Voltage (V) - Meas`: Measured output voltage in volts

### 2. Supplementary_Data_Figures_7_Temperature_Drift.xlsx

This file contains the temperature drift data of the DUT with the DG412 analog switch.
 Output voltage vs. temperature during 15°C → 35°C → 15°C cycling
 
**Columns:**
- `Temp2 - Temp2`: Internal DUT temperature measured by M1820Z sensor
- `Voltage (V) - Meas`: Measured output voltage in volts

### 3. Supplementary_Data_Figures_8_Temperature_Drift.xlsx

This file contains the temperature drift data of the DUT with the ADG452 analog switch.
 Output voltage vs. temperature during 15°C → 35°C → 15°C cycling

**Columns:**
- `Temp2 - Temp2`: Internal DUT temperature measured by M1820Z sensor
- `Voltage (V) - Meas`: Measured output voltage in volts

### 4. Supplementary_Data_Figures_9_Temperature_Drift.xlsx

This file contains the temperature drift data after software compensation.
 Output voltage vs. temperature after applying linear compensation algorithm

**Columns:**
- `Temp2 - Temp2`: Internal DUT temperature measured by M1820Z sensor
- `Voltage (V) - Meas`: Measured output voltage in volts

---

### 5. Supplementary_Data_Figures_10_11_Temperature_Drift.xlsx

This file contains the temperature drift data at 3V output before and after software compensation.
 Output voltage vs. temperature after applying linear compensation algorithm

**Columns:**
- `Temp2 - Temp2`: Internal DUT temperature measured by M1820Z sensor
- `Voltage (V) - Meas`: Measured output voltage in volts

### 6. Supplementary_Data_Figures_12_Temperature_Drift.xlsx

This file contains the temperature drift data at 6V output of ADR1399 before software compensation.
 Output voltage vs. temperature

**Columns:**
- `Temp2 - Temp2`: Internal DUT temperature measured by M1820Z sensor
- `Voltage (V) - Meas`: Measured output voltage in volts

### 7. Supplementary_Data_Figures_13_Temperature_Drift.xlsx

This file contains the temperature drift data at 6V output of ADR1399 before software compensation.
 Output voltage vs. temperature after applying quadratic compensation algorithm

**Columns:**
- `Temp2 - Temp2`: Internal DUT temperature measured by M1820Z sensor
- `Voltage (V) - Meas`: Measured output voltage in volts

---

## Experimental Setup

| Equipment | Model |
|-----------|-------|
| Digital Multimeter | Advantest R6581 (8.5-digit) |
| Temperature Chamber | DIY |
| Temperature Sensor | M1820Z |
| Oven-Controlled Voltage Reference | LTZ1000 |
| Analog Switches | DG412, ADG452 |

**Test Conditions:**
- Output voltage setpoint: 7.000000 V
- Temperature ramp rate: 0.002 °C/s
- Temperature range: 15°C → 35°C → 15°C

---

## Usage Notes

- All measurements are raw data as recorded, without any filtering or post-processing.
- The multimeter was operated in DC voltage-ratio function mode to minimize long-term drift.
- Time stamps are relative to the start of each experiment.

---

## License

This data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. You are free to share and adapt the data for any purpose, provided appropriate credit is given.

---

## Contact

For questions regarding this data, please contact:

Dunding Zuo  
Email: 1739687470@qq.com

---
