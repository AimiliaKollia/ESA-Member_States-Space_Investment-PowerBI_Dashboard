# ESA Member States Power BI Dashboard

Author: Aimilia Kollia

--- 

# Purpose: 
I developed a Power BI management dashboard to analyse ESA Member States’ space investments and contributions. The objective was to harmonise data from multiple sources and design KPIs that allow decision-makers to compare national space budgets, ESA contributions, and investment intensity across countries.

---

# Datasets:
The dashboard integrates three datasets. These datasets were cleaned, standardised, and merged using the country field as a key to create a unified analytical dataset.

• **_ESA Member State space budgets and ESA contributions from the ESPI Space Yearbook 2023_**
Source: https://www.espi.eu/wp-content/uploads/2024/08/ESPI-Yearbook-2023.pdf (section 3.3.2 National space budgets table)

• **_GDP data from Eurostat (tec00001 dataset)_**
GDP data for the UK was missing, so I found the GDP of the UK from a separate source to make the project and its insights more complete. UK GDP source: https://webgate.ec.europa.eu/isdb_results/factsheets/country/overview_united-kingdom_en.pdf (overview_united-kingdom_en_GDP.pdf)

• **_Population data from Eurostat (2022)_**
Similarly, population data for the UK was missing, so I found the Population of the UK from a separate source. UK 2022 Population source: https://cbonds.com/indexes/31789/

---

# Data preparation:
During preprocessing I handled missing values, standardised country names across datasets (e.g. Czech Republic was Czechia in some sources, which created inconsistencies), converted numerical formats, and structured the data to enable KPI calculations and comparisons.
Data transformation and cleaning were performed using Power Query before building the data model.
Furthermore, Data modelling was implemented in Power BI using a star-like structure to support efficient aggregation and filtering.

---

# KPIs Explanation:
I designed several KPIs to support strategic comparative analysis across ESA Member States. These key performance indicators (KPIs) were developed to evaluate space investment levels, economic context, and relative contributions.

# •	Total ESA Contribution (€M)
**Definition:** Total financial contribution of each ESA Member State to the European Space Agency in 2022.

**Purpose:** This measure aggregates the ESA contributions to provide a comparable overview of how much each country invests in ESA programmes.

# •	Total National Space Budget (€M)
**Definition:** Total national space budget allocated by each country in 2022.

**Purpose:** This metric represents the overall investment made by each country in space activities, including both ESA contributions and national space programmes.

# •	Total GDP (€M)
**Definition:** Gross Domestic Product of each country in 2022, expressed in million euros.

**Purpose:** GDP is used as an economic benchmark to compare space investments relative to the size of each country's economy.

# •	ESA Share (%)
**Definition:** Percentage of a country's national space budget that is allocated to ESA.

**Purpose:** This KPI shows how strongly each country relies on ESA programmes compared to their national space activities.

# •	ESA % of GDP
**Definition:** Ratio between a country's ESA contribution and its Gross Domestic Product.

**Purpose:** This indicator measures the economic weight of ESA contributions relative to the size of a country's economy, allowing fair comparison between large and small economies.

# •	ESA per Capita (€)
**Definition:** ESA contribution divided by the country's population.

**Purpose:** This KPI indicates the average ESA investment per citizen, helping to evaluate how much each country's population indirectly contributes to ESA activities.

# •	Total Space % of GDP
**Definition:** Ratio between the total national space budget and GDP.

**Purpose:** This measure evaluates how much each country invests in the space sector relative to its economic capacity.
These KPIs help evaluate both the scale of investment and the relative effort each country makes in the space sector using strategic KPI modelling. 

---

# Dashboard Structure:

# Page 1 (Executive Overview) - Overview of ESA Member States Investments 
The first page provides an overview of national space budgets and ESA contributions, allowing comparison across countries using KPI cards, bar charts, tables and geographical maps.
 

# Page 2 (Analytical Deep Dive) - Space Investment vs Economic Indicators
The second page analyses space investments relative to GDP and population, allowing the identification of countries that invest more intensively in space relative to their economic size.
 
# Dashboard Value for decision-making:
The dashboard supports management reporting by providing a structured and visual overview of ESA Member State investments. It allows stakeholders to quickly identify trends, compare contributions, and assess investment intensity across countries.

This directly connects to:
-	management dashboards
-	reporting platforms
-	decision support

Skills demonstrated:

- data integration
- data cleaning
- KPI modelling
- dashboard development using Power BI to support strategic reporting and decision-making.

# Conclusion:
I developed a Power BI management dashboard analysing ESA Member States’ space investments and contributions. I integrated datasets from the ESPI Space Yearbook and Eurostat, including space budgets, GDP and population data.
After cleaning and harmonising the datasets in Power Query, I designed KPIs such as space investment per capita, ESA contribution share, and space budget as a percentage of GDP. The dashboard provides an interactive overview of national space investments and allows comparison across countries, helping illustrate how different Member States contribute to and invest in the European space sector. The project demonstrates skills in data management, KPI modelling, and BI reporting.

