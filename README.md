## Overview
This repository contains a comprehensive analysis of land subsidence in North Jakarta, Indonesia, including spatial patterns, temporal trends, and future projections under various climate change and intervention scenarios. The analysis incorporates multiple datasets to understand the complex interplay between groundwater extraction, sea level rise, urbanization, and flooding risk.

## Background
North Jakarta faces one of the most severe land subsidence challenges globally, with some areas sinking at rates of 10-25 cm per year. This phenomenon is primarily driven by excessive groundwater extraction, compounded by rapid urbanization, natural soil compaction, and tectonic activities. The combination of land subsidence and accelerating sea level rise due to climate change presents an existential threat to this coastal urban region, which hosts critical national infrastructure including Indonesia's largest port (Tanjung Priok) and is home to over 1.5 million residents.

## Key Research Questions
1. What are the spatial and temporal patterns of land subsidence in North Jakarta?
2. How do groundwater extraction, sea level rise, and urbanization contribute to subsidence?
3. What are the projected impacts under different climate change scenarios?
4. Which adaptation strategies would be most effective and cost-efficient?
5. When will different areas of North Jakarta sink below sea level?

## Data and Methods
This analysis integrates several datasets:
- InSAR (Interferometric Synthetic Aperture Radar) subsidence measurements
- Sea level trends from tide gauges and satellite altimetry
- Groundwater extraction and depletion records
- Urbanization and population growth data
- Flood event frequency and severity
- Administrative boundaries of North Jakarta

Methods employed include:
- Spatial pattern analysis using clustering algorithms
- Multiple regression to identify key subsidence drivers
- Machine learning for future projections
- Cost-benefit analysis of adaptation strategies
- Combined sea level rise and subsidence modeling

## Key Findings
![jakarta_correlation_matrix](https://github.com/user-attachments/assets/b24824c1-cae0-43f7-a9d3-50602cb0fc53)

### Spatial Patterns of Subsidence
The analysis reveals distinct clusters of subsidence severity, with coastal areas experiencing the highest rates:
![jakarta_subsidence_map_2024_v2](https://github.com/user-attachments/assets/62459449-913b-406b-9d2e-2e8e0cad4bdb)
*Map showing land subsidence rates across North Jakarta*

### Temporal Trends
Subsidence rates have evolved over time, with some areas showing acceleration:
![jakarta_subsidence_temporal_trend](https://github.com/user-attachments/assets/189001cb-cee0-4f21-9c5c-5c75ea6057b4)
*Graph showing the evolution of subsidence rates from 2015-2024*

### Projections Under Different Scenarios
Different climate scenarios and intervention strategies yield significantly different outcomes:
![jakarta_subsidence_projections](https://github.com/user-attachments/assets/33019840-e25d-4c05-b3a0-86d272df40d3)
![jakarta_cumulative_subsidence_projections](https://github.com/user-attachments/assets/90ee685f-fa42-4d31-ac50-a69c0e280818)
*Projected subsidence under low, medium, and high impact scenarios*

### Effectiveness of Interventions
Our analysis indicates that comprehensive intervention strategies combining groundwater regulation, artificial recharge, and building code reforms yield the highest benefit-cost ratios:
![jakarta_intervention_effects](https://github.com/user-attachments/assets/30b8e5c7-d0e8-47c3-bc6d-771a51686254)
*Impact of different intervention strategies on cumulative subsidence*

### Submergence Timeline
Parts of North Jakarta are projected to sink below sea level in the coming decades:
![jakarta_key_dates_timeline](https://github.com/user-attachments/assets/7ec8ce3e-1c5f-4ef6-a1d4-80d198c7e7d3)
*Projected timeline for when different areas will sink below sea level*

## Key Recommendations
1. **Urgent Groundwater Regulation**: Implement strict groundwater extraction limits within the next 5 years
2. **Water Supply Alternatives**: Accelerate development of surface water treatment and distribution
3. **Targeted Managed Retreat**: Begin planned relocation from highest-risk coastal areas
4. **Infrastructure Protection**: Prioritize critical infrastructure for protective measures
5. **Monitoring System**: Enhance subsidence and groundwater monitoring networks

## Repository Structure
```
jakarta-subsidence-analysis/
├── North_Jakarta_Land_Subsidence_Analysis.ipynb (main analysis notebook)
├── README.md
├── requirements.txt
├── data/
│   ├── jakarta_subsidence_analysis/ (processed data)
│   ├── boundaries/ (administrative boundaries)
│   ├── sea_level_analysis/ (sea level rise data and projections)
│   └── integrated_analysis/ (combined analysis results)
└── visualizations/ (output visualizations)
```

## Setup and Usage
1. Clone the repository:
   ```
   git clone https://github.com/your-username/jakarta-subsidence-analysis.git
   cd jakarta-subsidence-analysis
   ```

2. Create a virtual environment and install dependencies:
   ```
   conda create -n jakarta-analysis python=3.9
   conda activate jakarta-analysis
   pip install -r requirements.txt
   ```

3. Download or prepare the administrative boundary shapefile:
   - Place the North Jakarta shapefile in `data/boundaries/north_jakarta/`
   - Ensure it contains administrative boundaries and is named `north_jakarta.shp`

4. Run the analysis notebook:
   ```
   jupyter notebook North_Jakarta_Land_Subsidence_Analysis.ipynb
   ```

## Future Work
1. Integration of high-resolution LiDAR elevation data
2. Development of a dynamic hydrological model
3. Inclusion of socioeconomic vulnerability metrics
4. Analysis of infrastructure damage costs
5. Extended analysis of saltwater intrusion impacts

## References
1. Abidin, H.Z., Andreas, H., Gumilar, I., Fukuda, Y., Pohan, Y.E., & Deguchi, T. (2011). Land subsidence of Jakarta (Indonesia) and its relation with urban development. *Natural Hazards*, 59(3), 1753-1771.
2. Emadodin, I., Taravat, A., & Rajaei, M. (2016). Effects of urban sprawl on local climate: A case study, north coastal city of Iran. *Urban Climate*, 17, 230-247.
3. IPCC. (2021). Climate Change 2021: The Physical Science Basis. Contribution of Working Group I to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change.
4. Takagi, H., Esteban, M., Mikami, T., & Fujii, D. (2016). Projection of coastal floods in 2050 Jakarta. *Urban Climate*, 17, 135-145.
5. World Bank. (2021). Toward a More Resilient and Livable Jakarta: Investing in Robust Infrastructure Solutions for Flood Risk Management.

## Contributors
- Riska Kuswati - Lead Researcher and Author

## License
This project is licensed under the MIT License - see the LICENSE file for details.
