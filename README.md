# CHAMP 0.0.1

**OBJECTIVES:**
- Gain familiarity with concepts and methods using simple models.
- Set data and model framework for further development.
- Develop hypotheses and interesting findings to explore in more detail.
- Examine emergent social-environmental phenomena caused by environmental heterogeneity.

**QUESTIONS - HYPOTHESES**
- How does environmental heterogeneity affect the degree to which self-governing groundwater conservation programs?
- Does above-ground or below-ground heterogeneity have a greater influence on groundwater use and conservation?

**SCENARIOS**
- Develop random heterogeneous fields of aquifer thickness and precipitation variability with different properties
- Run simulations with just heterogeneous precip, just heterogeneous aquifer, and both heterogeneous
- Run simulations with and without allowing cells to consider what is happening in neighboring cell when making decisions

## Models

### Crop model:
Water supply - yield relationship (Stone et al. 2006)
- Crops: Corn, Sorghum, Soybeans, and Wheat
- Input: Precipitation (m), Irrigation (m), Farm Area (m^2)
- Output: Yield (tons/m^2)
- Simulation time step: Yearly

### Groundwater model
KGS-WBM Water use - water-level change relationship (Butler et al. 2018) 
- Input: Initial water level (m), Water use (m^3), Farm area (m^2)
- Output: Water level (m), Stable pumping rate (m^3), Net inflow (m^3) 
- Simulation time step: Yearly

### Irrigation model 
Precipitation - Irrigation depth relationship (Glose et al. 2022)
- Input: Precipitation (m), Irrigation strategy (Pre or Post LEMA), Farm area (m^2)
- Output: Irrigation (m), Water use (m^3)
- Simulation time step: Yearly

### Agent Based Model
Consumat (Jager et al. 2000)
- Input:
- Output:
- Simulation time step: Yearly
