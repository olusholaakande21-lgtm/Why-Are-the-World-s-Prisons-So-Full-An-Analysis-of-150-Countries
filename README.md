# Why Are the World's Prisons So Full? An Analysis of 150 Countries

## Project Overview

This project uses **Microsoft Power BI** to investigate prison overcrowding, incarceration rates, pre-trial detention, and prisoner demographics across 150 countries.

Using data from the **World Prison Brief (2025)** and the United Nations Office on Drugs and Crime (UNODC), the project explores how prison occupancy, pre-trial detention, and justice-system characteristics relate to prison conditions worldwide.

The analysis follows a structured workflow encompassing a Pre-Analysis Board, interactive dashboard, In-Analysis Board, observations, and recommendations. The objective is to transform international prison statistics into meaningful insights that support evidence-based criminal justice policy and decision-making.

<img width="725" height="405" alt="Global Prison dashboard" src="https://github.com/user-attachments/assets/bebf1290-3b67-4b24-af06-3afbcbc12827" />


## Business Questions

1. Which regions and countries have the highest incarceration rates?
2. Which countries experience the most severe prison overcrowding?
3. How does pre-trial detention relate to prison occupancy?
4. Which subregions have the highest proportions of female prisoners?
5. Where are juvenile prisoners most prevalent?
6. Which countries have the highest proportions of foreign prisoners?
7. Is there a relationship between incarceration rates and prison occupancy?

## Dataset

* **Primary source:** World Prison Brief (2025)
* **Additional source:** UNODC prison and prisoner statistics
* **Coverage:** 150 countries
* **Scope:** Approximately 11.4 million prisoners represented across the countries studied
* **Additional data:** Regional summaries and historical UNODC data covering 1998–2024

Key variables include total prisoners, incarceration rates per 100,000 people, prison occupancy levels, and the proportions of prisoners awaiting trial, female, juvenile, or foreign.

## Tools and Technologies

* **Power BI Desktop:** Data modelling, visualization, and dashboard development
* **Power Query:** Data import, transformation, and preparation
* **Interactive reporting:** KPI cards, charts, and country and region slicers

## Data Preparation

The data preparation process included:

* Promoting headers and assigning appropriate data types.
* Preparing country-level and regional summary tables.
* Connecting the country dataset to regional and UNODC data.
* Reviewing missing values and validating calculated measures against the source data.

An important limitation was identified: some missing values were replaced with zero. This affected occupancy and prisoner-demographic measures and could understate regional averages. These values should be treated as potential missing data rather than confirmed zeros.

## Key Findings

### 1. Prison overcrowding is widespread

Of the 140 countries reporting occupancy levels, **99 countries (71%) operated above official prison capacity**, while 48 (34%) exceeded 150% occupancy.

Africa had the highest average occupancy among the regions studied, at approximately 184.6%.

### 2. Some prison systems face extreme overcrowding

Cambodia recorded approximately 409% occupancy, followed by the Philippines at 362% and Uganda at 342%.

These figures indicate severe pressure on available prison infrastructure.

### 3. Pre-trial detention is associated with overcrowding

Average occupancy increased across the three groups of countries ranked by pre-trial detention share:

* Lowest third: 113%
* Middle third: 139%
* Highest third: 174%

The correlation between pre-trial detention share and occupancy was approximately **0.42**, indicating a moderate positive relationship. This association does not establish causation.

### 4. Incarceration rates do not necessarily predict overcrowding

The Americas had the highest average incarceration rate, at approximately 339 prisoners per 100,000 people. Africa had the lowest regional average, at approximately 137.

However, Africa had the highest average prison occupancy. The correlation between incarceration rate and occupancy was approximately −0.05, showing almost no linear relationship in this dataset.

### 5. Prisoner demographics reveal additional policy considerations

Women accounted for approximately 5% of prisoners on average, while juveniles represented approximately 1.4%.

The United Arab Emirates had the highest reported share of foreign prisoners among the countries examined, at 87.8%.

These findings highlight the importance of considering gender-responsive justice, juvenile diversion, legal representation, and the circumstances of foreign nationals in detention.

## Data Validation and Lessons Learned

Cross-checking dashboard calculations against the underlying data revealed three important issues:

* **Incorrect aggregation of rates:** Summing country incarceration rates distorted regional comparisons. Average rates provided a more meaningful comparison.
* **Misinterpretation of chart percentages:** A country's share of a selected chart total was not the same as the percentage of its prisoners who were foreign.
* **Incorrect aggregation of percentages:** Adding country-level percentages produced misleading KPIs. Appropriate averages or prisoner-weighted percentages are required, depending on the question.

These checks reinforced the importance of validating measures, choosing appropriate aggregations, and verifying dashboard outputs before communicating findings.

## Recommendations

1. **Address overcrowding:** Assess prison capacity and develop costed plans to reduce occupancy in severely overcrowded systems.
2. **Review pre-trial detention:** Consider faster case processing, appropriate bail systems, and non-custodial alternatives where legally suitable.
3. **Improve sentencing policy:** Evaluate alternatives to imprisonment for appropriate non-violent offences.
4. **Strengthen gender-responsive justice:** Review policies affecting women in detention and consider appropriate alternatives for low-level offences.
5. **Protect children:** Expand diversion programmes and youth justice alternatives in line with applicable child-protection standards.
6. **Support foreign prisoners:** Improve access to legal assistance, interpretation, and consular support.
7. **Improve data quality:** Preserve missing values as missing, distinguish estimates from confirmed figures, and standardize international reporting.

## Limitations

* The dashboard primarily uses a 2025 country snapshot rather than visualizing the full historical UNODC time series.
* Some missing values were replaced with zero, potentially understating selected measures.
* Twenty-three country records were identified as estimates.
* Reporting coverage and standards vary across countries.
* Correlation does not establish causation; the observed relationships cannot independently prove the causes of overcrowding.

## Skills Demonstrated

Power BI | Power Query | Data Modelling | Data Cleaning | KPI Development | Data Visualization | Exploratory Data Analysis | Statistical Interpretation | Data Validation | Dashboard Development | Analytical Storytelling | Evidence-Based Recommendations


