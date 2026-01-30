# Growth in Dried Onion Use (2007–2024)

This project analyzes long-term trends and drivers of dried onion use using official open data from OpenData.az.  
The analysis focuses on identifying structural changes over time and understanding which components contribute most to overall growth.

---

## Data Source

- **Dataset:** Uses of dried onions (annual indicators)
- **Provider:** OpenData.az (official government open data portal)
- **Time period:** 2007–2024
- **Unit:** Tons

The dataset includes annual figures for:
- household consumption
- exports
- seed use
- losses
- end-of-year stocks
- total use

---

## Methodology

The analysis follows a structured, transparent approach:
1. Data validation and consistency checks
2. Time-series trend analysis
3. Year-over-year growth assessment
4. Decomposition of total growth by use components
5. Contribution analysis to identify primary growth drivers

All computations were performed using Python (pandas, Plotly).

---

## Key Findings

- Total dried onion use increased by approximately **208,000 tons** between 2007 and 2024.
- Growth accelerated significantly after **2018**, with average annual growth rising from ~0.7% to ~9.3%.
- **Household consumption** is the dominant driver, accounting for **63% of total growth**.
- **End-of-year stocks** contribute around **20%**, suggesting changing storage or inventory dynamics.
- **Exports** play a relatively minor role, contributing less than **6%** of growth.
- **Seed use** remains flat to slightly declining.

---

## Context and Background

Previous research suggests that dehydrated onions can be stored for up to **12 months** under proper conditions, which improves transport safety and supply-chain flexibility.  
This characteristic helps explain the importance of domestic consumption, storage behavior, and inventory management observed in the data.

---

## References

Rodriguez, J. R., & Kim, S. J. (2022). *Sustainability implications of post-harvest technology adoption*. Global Environmental Studies, 45(5), 201–220.

---

## Files in this Repository

- `GrowthInDriedOnionUse.ipynb`
- `GrowthInDriedOnionUse.html` 
