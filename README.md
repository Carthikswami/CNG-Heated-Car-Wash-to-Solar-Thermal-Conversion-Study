# CNG-Heated Car Wash to Solar Thermal Conversion Study

This repository documents an engineering and financial study evaluating the feasibility of converting an existing CNG-heated car wash system to a solar thermal water-heating solution. The study is motivated by rising fuel costs, carbon reduction goals, and the potential for improved operational efficiency through renewable heat technologies.

The analysis focuses on technical performance, system sizing, and cost-effectiveness across the full lifecycle.

---

## Study Objectives

1. Quantify the hot water and thermal load profile of a typical car wash facility.
2. Model the current energy consumption and cost of a CNG-based heating system.
3. Evaluate the feasibility of replacing or supplementing CNG with solar thermal collectors.
4. Size a solar thermal system based on load, location-specific irradiance, and collector performance.
5. Conduct a financial analysis including payback, NPV, IRR, and sensitivity to fuel price changes.
6. Assess operational constraints, maintenance requirements, and real-world deployment considerations.

---

## Technical Approach

### Load Assessment
- Hourly and daily hot-water consumption estimates.
- Temperature rise requirements for wash cycles.
- Conversion of water demand to thermal energy load (BTU or kWh).
- Seasonal variability and peak-demand considerations.

### Existing CNG System
- Burner efficiency assumptions.
- CNG usage estimation based on heat load.
- Operating cost calculation using utility rate data.

### Solar Thermal System Design
- Evaluation of flat-plate vs evacuated-tube collectors.
- Collector efficiency curves, optical parameters, and thermal losses.
- System configuration: storage tank, pump loop, heat exchanger, auxiliary heater.
- Collector area sizing based on desired solar fraction.
- Estimation of useful heat gain using location-specific solar data.

### Performance Evaluation
- Annual useful energy yield.
- Solar fraction and displacement of CNG consumption.
- Temperature maintenance and backup requirements.

Detailed spreadsheets and diagrams are included in the `thermal-design/` and `load-analysis/` directories.

---

## Financial Modeling

The economic model evaluates multiple deployment pathways:

- Full replacement of CNG heating.
- Hybrid operation (solar pre-heating + CNG backup).
- Different collector sizes and capital cost assumptions.

The financial model includes:

- Installed equipment cost (collectors, controls, circulation system)
- Operating and maintenance costs
- Fuel price escalation scenarios
- Incentives (tax credits, rebates, depreciation if applicable)
- 20–25 year lifecycle analysis

Sensitivity analysis is included to test the impact of fuel prices, solar fraction, and collector efficiency. Files are located in the `financial-model/` folder.

---
