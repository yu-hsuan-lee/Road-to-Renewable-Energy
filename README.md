# Road-to-Renewable-Energy

## Overview
This repository examines the global shift from fossil fuels to renewable energy, exploring *why* this transition is happening, *which factors drive it*, and *how different countries are responding.* By integrating data on renewable energy output with economic, environmental, and social indicators, we uncover patterns, disparities, and opportunities in global clean energy adoption.

## Key Insights
- **A Defining Turning Point:**  
  Around 1999–2000, global renewable energy production surged by 52.5%, indicating a profound strategic shift. This inflection point aligns with international climate agreements (e.g., Kyoto Protocol) and increased investment in clean technologies.

- **Developed vs. Developing Nations:**  
  While developed countries historically produced more renewable energy due to established infrastructures and capital, certain developing nations—like China and Brazil—have caught up rapidly. By 2020, developing countries even surpassed developed ones in total renewable output, driven by these high-performing outliers.

- **Drivers of Renewable Adoption:**  
  - **Economic Capacity:** Wealthier countries more readily invest in renewable infrastructure, as reflected by GDP and urbanization metrics.  
  - **Environmental Urgency (CO₂ Emissions):** High-emission countries highlight the need for clean energy, but entrenched fossil fuel use can impede rapid renewable uptake.  
  - **Geographical Feasibility (Land Area):** Larger land areas support extensive solar, wind, and hydro installations.  
  - **Socio-Demographics (Urban Population):** Urbanization can spur energy innovation but may also expose infrastructural and spatial challenges in implementing renewables at scale.

- **Policy and Technological Influences:**  
  Agreements like the Kyoto Protocol (1997) and the Paris Agreement (2015) fostered international collaboration, while advancements in solar, wind, and other technologies helped normalize renewables as a central energy source.

## Analytical Approach
1. **Data Integration:**  
   Merged renewable energy production data with country-level economic, environmental, and demographic indicators.

2. **Exploratory Data Analysis (EDA):**  
   - Identified the 1999–2000 surge in renewable energy production.  
   - Compared developed vs. developing nations, revealing how certain countries drive global trends.  
   - Conducted Chi-square tests to confirm associations between development status and renewable energy output.

3. **Variable Selection & Transformation:**  
   - Evaluated correlations and addressed multicollinearity by creating composite indices (e.g., Economic Index).  
   - Used log transformations for highly skewed variables (GDP, CO₂ emissions, land area) to improve model stability and interpretability.

4. **Regression Modeling:**  
   A regression model explained ~50% of the variation in renewable output. Results show that:
   - Higher economic capacity and larger land areas correlate with more renewables.  
   - Higher CO₂ emissions correlate negatively, suggesting policy and infrastructural barriers.

5. **K-Means Clustering:**  
   Grouped countries into three clusters by economic, environmental, and geographic traits. These clusters highlight diverse pathways and hurdles in renewable adoption.

## Why This Matters
- **Policy Guidance:** Identifying key drivers helps policymakers design targeted financial incentives, infrastructure investments, and regulations.
- **Strategic Investments:** Insights guide private-sector decisions, focusing innovation where it can most effectively boost clean energy.
- **Global Equity:** Highlights the importance of international collaboration to help resource-constrained countries adopt cleaner energy at scale.

## References
- [Countries of the World 2023 (Kaggle)](https://www.kaggle.com/datasets/nelgiriyewithana/countries-of-the-world-2023)
- [Global Fossil CO₂ Emissions (Kaggle)](https://www.kaggle.com/datasets/thedevastator/global-fossil-co2-emissions-by-country-2002-2022)
- [Kyoto Protocol - UNFCCC](https://unfccc.int/kyoto_protocol)
- [The Paris Agreement - UNFCCC](https://unfccc.int/process-and-meetings/the-paris-agreement)
- [UN Country Classification](https://www.un.org/en/development/desa/policy/wesp/wesp_current/2014wesp_country_classification.pdf)

