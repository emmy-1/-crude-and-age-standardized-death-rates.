# CASE STUDY : CHRONIC OBSTRUCTIVE PULMONARY DISEASE IN USA AND UGANDA

**Chronic obstructive pulmonary disease (COPD)** is a *progressive lung condition* characterized by obstructed airflow, making breathing difficult. This report outlines the steps and code used to calculate the crude and age-standardized death rates (SDRs) for COPD in the US and Uganda (2019).

### What is the Crude Death Rate (CDR) ?

Measures proportion of population dying from a specific disease. Calculated by dividing deaths by total population x a scale (100,000). one of the major drawbacks is it Doesn't account for age, sex, and demographics, leading to potential bias. to accurately compare the rates we need to apply age standardization. Given that the age distribution can differ significantly from one country to another over time, making this adjustment enables us to observe variations in death rate without the influence of age disparities.

### Age-Standardized Death Rate (ASDR)?
Adjusts rates for different age distributions to enable fair comparisons. calulated by Multiply age-specific death rates by standard population distribution

### Code Steps:

1. Import and clean COPD data (US & Uganda) from a CSV.
2. Sumed the total death Rate and Calculate CDRs for each country.
3. Source standard population data.
4. Joined COPD and Who World age standardization Data:
5. Multiplied age-specific death rates by standard population distribution.
6. Sum the rates to obtain the ASDR. -- **Note : This was not asked for and can be ignored**.

### Observations:

Crude death rate was higher in Uganda, possibly due to limited healthcare, nutrition, and higher infectious diseases.
Age-standardized death rate remained higher in Uganda except for 50-59 and 85+ age groups.

### Assumptions:
Reliable and consistent death reporting and population estimates.
Accurate cause of death identification in both countries.
