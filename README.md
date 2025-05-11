# Data-Visualization-Project

# Project: Visualizing Global Development Dynamics

## Overview

This project delves into global development trends by leveraging data from the World Bank. Our objective was to transform complex, multifaceted datasets into clear, interactive, and insightful visualizations. We aimed to uncover patterns, disparities, and correlations in areas such as economic inequality, gender dynamics, health outcomes, and educational attainment across various countries and regions.

The project involved a data pipeline using Python for comprehensive data acquisition and preprocessing, followed by the creation of compelling dashboards and reports using Tableau and Power BI and Canva. All our finalized visualizations are showcased on our dedicated project website.

**Explore the Visualizations:** [https://projectdatavisual.altervista.org/]

## Data Source

The core data for this project was sourced from:
*   **World Bank Open Data:** [https://github.com/light-and-salt/World-Bank-Data-by-Indicators/tree/master]

We worked with four distinct datasets from the World Bank: EDUCATION, GENDER, POVERTY, SOCIAL DEVELOPMENT focusing on indicators related to:
*   Economic Inequality (e.g., Gini Index)
*   Gender-specific data (e.g., employment, education, health, fertility rates)
*   Poverty and Social Development
*   Education metrics
*   Health indicators (e.g., mortality rates)

## Note: in the zip file you will find both the raw datasets and also the final dataset, to reproduce the visualization, use the final dataset.

## Technologies Used

*   Data Acquisition & Preprocessing:
    *   Python 3.12
        *   Pandas: For data loading, cleaning, transformation, merging, and analysis.
        *   NumPy: For numerical operations.
        *   Matplotlib: For Exploratory Data Analysis
        
*   **Data Visualization & Dashboarding:**
    *   Tableau Desktop
    *   Microsoft Power BI Desktop
    *   Canva
*   **Web Hosting:**
    *   Altervista (for the project showcase website)

## Data Processing with Python (The "Behind the Scenes")

Python key steps include:

1.  **Data Loading:** Loading the four distinct datasets (related to poverty, social development, gender, education, etc.) from their raw formats.
2.  **Data Cleaning:**
    *   Handling missing values: Strategies included identifying columns with high percentages (60%) of missing data and dropping them.
    *   Removing irrelevant columns or rows (e.g., aggregated regional data not needed for country-level analysis).
    *   Standardizing data, such as mapping country names to consistent regions/continents.
3.  **Data Transformation & Feature Engineering:**
    *   Merging different datasets to create a comprehensive dataset for analysis.
    *   Creating new features or calculating derived metrics (e.g., calculating Gender Parity Index (GPI), calculating average values).
    *   Restructuring data for specific visualization needs.
4.  **Exploratory Data Analysis (EDA):** 
    *   Examination of the merged dataset to understand the finals feature structure, identify data types, distributions.
5.  **Output:** Exporting the cleaned and processed dataset into formats suitable for Tableau and Power BI.

## Key Visualizations & Insights on the Website

Our project website ([https://projectdatavisual.altervista.org/](https://projectdatavisual.altervista.org/)) showcases a variety of interactive visualizations. Here are some highlights:

1.   **Let's Start with the Big Picture: A Global View (Global Flows of Women's Lives):**
    *   **Description:** A Sankey diagram illustrating the flow of women through different life stages: Enrollment Level, Employment Level, and Fertility Level. Accompanied by a bubble chart showing average female life expectancy by continent, with bubble size correlated to poverty rates.
    *   **Potential Insights:** Visualizes pathways in women's lives concerning education, work, and family, and correlates life expectancy with economic conditions.

2.  **Zooming In: Disparities Across Regions (Adult Mortality):**
    *   **Description:** A radar chart comparing average adult mortality rates (per 1,000 adults) for males and females across different global regions.
    *   **Potential Insights:** Highlights regional and gender-based disparities in health outcomes and life expectancy, in particular in the Sub-Saharian Africa we observe high values of mortality.

3.  **Global Decline in Fertility Rates (1960-2020):**
    *   **Description:** A line chart tracking the average births per woman across various global regions from 1960 to 2020. Interactive tooltips provide specific values.
    *   **Potential Insights:** Shows the demographic transition of declining fertility rates, with regional variations.

4. **White Hat vs. Black Hat: The Power of Framing (Female Education & Job Vulnerability):**
    *   **Description:** A scatter plot examining the relationship between Female Secondary School Enrollment Rate (%) and Female Vulnerable Employment Rate (%). It highlights zones indicating correlation.
    *   **Potential Insights:** Suggests the positive impact of female education on economic security.

5. **Bubble Chart – School Enrollment vs Employment Vulnerability:** 

    *   **Description:** An interactive bubble chart tracking the relationship between female secondary school enrollment and vulnerable employment rates from 1990 to 2019. Each bubble represents a country, with its size reflecting female mortality. We selected a few top-performing and underperforming countries to highlight the stark differences in trends across the years.
    *   **Potential Insights:** Users can explore how different countries evolve over time.

6. **Regional Constellations – A Creative Visualization of Inequality:**
 *   **Description:** A symbolic star map where each region is visualized as a constellation. The main star's size encodes income inequality (Gini Index),
     its color shows gender equality, and its glow represents life expectancy. The surrounding small stars reflect female education levels (quantity) and adolescent fertility rates (color).
*   **Potential Insights:** This creative layout allows viewers to instantly compare regions and explore how multiple development dimensions interact. 

7.  **Gini Index – A Global Perspective on Inequality:**
    *   **Description:** An interactive world map color-coded by the Gini Index, offering a quick visual understanding of income inequality levels across countries. It also displays key statistics like the percentage of unemployed males and females for selected countries.
    *   **Potential Insights:** Quickly identify regions/countries with high or low income disparity.


## How to Explore Our Work

1.  Visit our project website: **[https://projectdatavisual.altervista.org/](https://projectdatavisual.altervista.org/)**
2.  Navigate through the different pages or sections to view the interactive dashboards.
3.  Utilize the filters, tooltips, and other interactive elements within the Tableau and Power BI visualizations to dive deeper into the data.

## Authors
*   Joel Sonnino, Carlotta Menasci, Paolina Mazza, Arnur Nurakhmetov

