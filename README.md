# sour-gas-sweetening-hysys
Steady-state simulation of a sour gas sweetening process using Diethanolamine (DEA) in Aspen HYSYS.
# Comprehensive Simulation Report: Sour Gas Sweetening via DEA

**Author:** Mahdi Arashian  
**Institution:** University of Bojnord  

## 1. Introduction
This document provides the full design parameters and results for the simulation of a Sour Gas Sweetening unit performed in Aspen HYSYS.

## 2. Process Design Data

### 2.1. Feed Gas (Sour Gas)
| Parameter | Value |
|---|---|
| Temperature | 86 °F |
| Pressure | 1000 Psia |
| Molar Flow | 25 MMSCFD |

**Composition (Mole Fraction):**
| Component | Value |
|---|---|
| Nitrogen | 0.0016 |
| CO2 | 0.0413 |
| H2S | 0.0172 |
| Methane | 0.8692 |
| ... | (See tables in report) |

### 2.2. Solvent (DEA)
| Parameter | Value |
|---|---|
| Temperature | 95 °F |
| Pressure | 995 Psia |
| Flowrate | 190 USGPM |

### 2.3. Regeneration Column Specs
| Property | Value |
|---|---|
| Total Trays | 18 |
| Condenser P | 27.5 Psia |
| Reboiler P | 31.5 Psia |
| Reboiler Duty | 1.356e7 Btu/hr |

## 3. Results Summary
- **H2S in Sweet Gas:** < 0.0001 (Trace)
- **CO2 in Sweet Gas:** 0.0012
- **System Convergence:** Successfully converged with Recycle loop.
