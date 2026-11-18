### California Housing Price Analysis Dashboard | Power BI

#### Project Overview

This project uses Power BI to analyze California housing data, focusing on house values, median income, housing age, residential structure, population distribution, and geographical factors. This report employs various visualizations—including scatter plots, bar charts, and matrices—to help users understand the relationships between housing prices, income, and geographical location in California, thereby providing them with a useful frame of reference.



#### Project Objectives

Analyze the distribution of median house values across different geographical areas.

Explore the relationship between median income and house values.

Investigate how housing age influences property values.

Analyze the relationship between population, households, rooms, and bedrooms.

Identify key factors influencing regional house values.



#### Data Modeling

FactHousing: Main housing data, including house values, median income, housing age, population, households, rooms, bedrooms, and geographical coordinates.

DimOceanProximity: Ocean proximity categories for geographical analysis.

DimIncomeBand: Income classification for comparing house values across different income groups.

DimAgeBand: Housing age classification for analyzing property value patterns.

DimLocation: Geographical information



#### Dashboard Pages \& Analysis

Page 1 -- House Value Overview -- Overall housing market and geographical distribution

Key visualizations:

KPI Cards: average house value, average housing age, average income, and housing area count.

Map: Geographical distribution of housing areas and house values.

Clustered Bar Chart: House value comparison across different ocean proximity categories.

In California, housing prices are largely driven by location, particularly to the coast. Coastal and Bay Area properties tend to be significantly more expensive, while inland areas generally offer lower housing costs.



Page 2 -- Income \& House Value -- Relationship between income and property values

Key visualizations:

Scatter Chart: Correlation between median income and median house value.

Clustered Column Chart: Average house value by income band and ocean proximity.

Clustered Column Chart: House value comparison across different income groups.

Matrix: House value differences across income bands and ocean proximity.

In California, housing prices are influenced by income levels and proximity to the coast. Coastal areas with higher incomes see the highest prices, while inland regions with lower incomes offer more affordable housing. The $500,000 price ceiling also has an impact on market analysis.



Page 3 -- House Value \& Residential Structure -- Housing characteristics and residential patterns

Key visualizations:

Clustered Column Chart: Average house value across different housing age groups.

Scatter Chart: Relationship between population per household and rooms per household.

Scatter Chart: Relationship between house value and bedroom-to-room ratio across geographical areas.

Matrix: House value comparison across income bands and housing age groups.

Interactive slicers for income bands and ocean proximity.

Income and location are the primary drivers of California housing prices, while property age and room structure have a smaller impact. Analysis should prioritize income levels and coastal proximity, carefully handle outliers in room and population counts.



Page 4 -- Geographic Analysis of House Value -- Factors influencing regional property values

Key visualizations:

Decomposition Tree: Analysis of factors influencing median house values by ocean proximity, income band, and housing age group.

Clustered Bar Chart: Median house value comparison across ocean proximity categories.

Interactive slicer for ocean proximity.

Location is a major factor in California house prices, with homes closer to the coast usually costing more. Income and house age also affect prices, but to a lesser extent. The analysis should focus on the differences between coastal and inland areas, looking at how income and house age affect prices in each area.



#### Key Skills Demonstrated

Data Cleaning \& Transformation

Power Query (ETL)

DAX Measures \& Calculations

Data Modeling

Star Schema Design

Exploratory Data Analysis (EDA)

Statistical \& Correlation Analysis

Data Visualization

Business Intelligence



#### Final Conclusion

In California, house prices are mainly affected by location and income. Coastal homes are almost twice as expensive as inland homes, while prices can be more than three times higher across income groups. High-income coastal areas have the highest house prices, while low-income inland areas have the lowest. The age and size of houses have little impact on prices. The $500K price limit also means that expensive homes may be valued too low, making it harder for people to buy homes in coastal areas.

