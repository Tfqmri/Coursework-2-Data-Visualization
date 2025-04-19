# Coursework-2-Data-Visualization
# Dietary Emissions Visualization – Treemap Analysis

This project explores greenhouse gas (GHG) emissions from diet across demographic groups, using treemap visualizations and supplementary plots.

## Contents

- `Results_21Mar2022.csv`: Original dataset containing dietary and demographic data.
- `processed_ghg_data.csv`: Cleaned dataset with calculated total and mean GHG emissions.
- `treemap_final_export.png`: High-resolution treemap image showing GHG emissions by sex, age group, and diet type.
- `treemap_final_interactive.html`: Interactive treemap file for dynamic exploration of group-level emissions.
- `boxplot_meat100_sex_agegroup.png`: Boxplot comparing per-capita GHG emissions across age groups and sex (Meat100 only).
- `mean_std_ghgs_meat100_by_sex.png`: Bar chart showing group means ± standard deviation for per-capita emissions.
- `sorted_by_mean_ghgs.csv`: Summary table sorted by per-capita GHG emissions.
- `sorted_by_total_ghgs.csv`: Summary table sorted by total GHG emissions.

## Method Overview

1. **Data Preprocessing**  
   - Selected relevant columns  
   - Cleaned missing values  
   - Calculated per-capita (`mean_ghgs`) and total (`total_ghgs`) emissions  

2. **Treemap Visualization**  
   - Hierarchy: sex → age_group → diet_group  
   - Area encodes total GHG emissions (kg CO₂e/day)  
   - Color encodes mean GHG emissions per person  

3. **Further Analysis of Unique Observation**  
   - Investigated unusually high emissions in older male Meat100 group  
   - Verified consistency using boxplots and mean ± SD analysis  

## Video Presentation (Optional)

🎥 Watch the full explanation and walkthrough here:  
[`https://your_video_url_here`  
*(Replace with actual link after uploading)*
](https://youtu.be/0mZXKyyYFU8?si=ORoL6_ZG9JHZewOJ)
## Interactive Version

🌐 Explore the interactive treemap locally:  
Open the following file in your browser:  
`treemap_final_interactive.html`

---

© 2025 University of Nottingham | Coursework Project for COMP4037 – Research Methods
