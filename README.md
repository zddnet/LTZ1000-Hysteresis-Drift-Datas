# Supplementary Data for: Software-Based Thermal Hysteresis Elimination and Drift Compensation for an Oven-Controlled Voltage Reference

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

---

## File Descriptions

### 1. Supplementary_Data_Figures_3_to_6_Hysteresis.xlsx

This file contains the output voltage measurements during thermal hysteresis elimination experiments under three operating conditions:

| Sheet Name | Description |
|------------|-------------|
| `Fig3_Continuous` | Complete output voltage waveform during thermal cycling under continuous power |
| `Fig4_Zoomed` | Zoomed view of output voltage before and after thermal cycling (continuous power) |
| `Fig5_1.5h_Off` | Output voltage before/after 1.5 h power interruption and after one thermal cycle |
| `Fig6_11.5h_Off` | Output voltage before/after 11.5 h power interruption and after one thermal cycle |
	
**Columns:**
- `Time - Meas`: Elapsed date-time
- `Voltage (V) - Meas`: Measured output voltage in volts

### 2. Supplementary_Data_Figures_7_Temperature_Drift.xlsx

This file contains the temperature drift data of the DUT with the DG412 analog switch.

| Sheet Name | Description |
|------------|-------------|
| `Fig7_DG412` | Output voltage vs. temperature during 15°C → 35°C → 15°C cycling |

**Columns:**
- `Temp2 - Temp2`: Internal DUT temperature measured by M1820Z sensor
- `Voltage (V) - Meas`: Measured output voltage in volts

### 3. Supplementary_Data_Figures_8_Temperature_Drift.xlsx

This file contains the temperature drift data of the DUT with the ADG452 analog switch.

| Sheet Name | Description |
|------------|-------------|
| `Fig8_ADG452` | Output voltage vs. temperature during 15°C → 35°C → 15°C cycling |

**Columns:**
- `Temp2 - Temp2`: Internal DUT temperature measured by M1820Z sensor
- `Voltage (V) - Meas`: Measured output voltage in volts

### 4. Supplementary_Data_Figures_9_Temperature_Drift.xlsx

This file contains the temperature drift data after software compensation.

| Sheet Name | Description |
|------------|-------------|
| `Fig9_Compensated` | Output voltage vs. temperature after applying linear compensation algorithm |

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
