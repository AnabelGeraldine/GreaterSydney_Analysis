# GreaterSydney_Analysis
- Enhances geospatial data analysis through the use of tools like geopandas for GIS data manipulation,
and advanced data processing skills in cleaning, transforming, and integrating datasets into SQL
databases.
- Refine statistical analysis techniques by computing and interpreting z-scores and their socio-economic
implications. The project also develops your ability to create interactive maps and visual representations,
essential for effective data communication.
- Hones critical thinking through correlation analysis and report writing skills, culminating in a
comprehensive presentation of findings. These competencies are crucial for careers in urban planning, data analytics, public policy, and GIS, making this a significant professional development experience.

## Problem Statement
This project analyzes resource distribution across the Greater Sydney area, focusing on Statistical Area Level 2 (SA2) regions. The goal is to develop a well-resourced score that reflects the availability of essential services such as retail businesses, healthcare, public transport stops, polling places, and schools. The project aims to help individuals, businesses, and policymakers assess which areas have better access to resources and which regions may need improvement.

## Methods and Tools Used
The analysis involved data preprocessing, database management, and statistical modeling. Various datasets were collected, including business counts, transport stops, polling places, school catchments, income levels, and population statistics. Using Python (pandas, geopandas, matplotlib) and SQL, the data was cleaned, transformed, and stored in a structured database. A z-score normalization and logistic function were applied to compute a standardized resource score for each region. Additionally, an interactive geospatial visualization was developed to illustrate the results.

## Findings and Results
The analysis revealed significant variation in resource distribution across different SA2 regions. The highest well-resourced scores were found in areas like Millers Point and Baulkham Hills, while regions like Lilli Pilli and Summerland Point had the lowest scores. A correlation analysis between resource scores and median income indicated a weak negative correlation, suggesting that resource availability is not directly linked to income levels. The scoring model was later extended by incorporating rent and public toilet data, providing a more comprehensive assessment of accessibility, though some missing data posed limitations.

## Future Work
 Future improvements could involve integrating more current datasets, considering additional socio-economic variables, and refining the scoring methodology to create a more accurate representation of well-resourced regions in Greater Sydney.
