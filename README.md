# Global Infectious Disease Surveillance | Business Intelligence Case Study

## Global Tuberculosis Burden & Resource Alignment

This Business Intelligence case study explores global tuberculosis (TB) burden, disease intensity, and the alignment of reported program resources with areas of greatest need using publicly available World Health Organization (WHO) data.

The project demonstrates an end-to-end analytical workflow—from data preparation and validation through business analysis, data modeling, and executive-level visualization.

### Business Questions

The analysis is organized around two connected questions:

1. **Where is TB need greatest?**
2. **How do reported program resources and utilization compare with these areas of need?**

### Analytics Workflow

**WHO TB Data → Python: Prep & Validation → MySQL: Analysis → Power BI: Modeling & Insights**

### Power BI Case Study

The final Power BI report consists of two connected analytical views:

**1 | Global TB Burden & Resource Prioritization**  
Examines estimated TB burden and population-adjusted incidence to identify countries where both measures indicate particularly high need.

**2 | TB Resource Allocation & Program Alignment**  
Extends the analysis into reported program budgets, expenditures, resource utilization, and the relationship between disease burden and reported resources.

>## Power BI Visual Walkthrough

The Power BI case study is presented through two short visual walkthroughs that demonstrate the analytical progression from identifying areas of high TB need to examining reported program resources and utilization.

### 1 | Where Is TB Need Greatest?

Explore 2024 estimated TB burden, population-adjusted incidence, and the identification of countries meeting the project's combined High-Burden / High-Incidence criteria.

▶ **[Watch Video 1 — TB Burden & Resource Prioritization](https://drive.google.com/file/d/1RgeCHVGN_azYxFJXzEmvZF_x9hAEINKp/view?usp=drive_link)**

### 2 | Are Resources Aligned With Areas of Greatest Need?

Explore reported TB program budgets, expenditures, resource utilization, and the relationship between disease burden and reported resources during the 2018–2024 analysis period.

▶ **[Watch Video 2 — TB Resource Allocation & Program Alignment](https://drive.google.com/file/d/1qVQCsyuJqicIZijLl8HI0YRj2CYeWtQY/view?usp=drive_link)**

---

## Key Insights

- An estimated **10.6 million TB cases** were identified globally for 2024 in the analysis.
- Countries with the greatest estimated TB case burden are not necessarily the countries with the highest population-adjusted TB incidence.
- **Seven countries** met the project's combined High-Burden / High-Incidence criteria, highlighting areas for further resource-allocation assessment.
- Across reported TB program data for **2018–2024**, total expenditure represented **68.5% of reported budget**.
- Resource utilization differed substantially by program component: **staff budget utilization was 92.1%**, compared with **38.3% for laboratory resources**.
- Among high-burden countries with complete 2018–2024 financial reporting, several countries showed reported budget utilization near or below one-third, identifying areas for further investigation of resource deployment and alignment with TB burden.

> These findings identify patterns and areas for further investigation. They should not be interpreted as conclusions about funding adequacy, program effectiveness, or causality.

---

## Analytical Methodology

### TB Burden & Incidence

The 2024 analysis examines two complementary measures:

- **Estimated TB cases** — representing absolute disease burden.
- **TB incidence per 100,000 population** — representing population-adjusted disease intensity.

For this case study, a **High-High priority country** was defined as having:

- **≥ 100,000 estimated TB cases**, and
- **≥ 300 TB cases per 100,000 population**

A prioritization score was then used to compare countries meeting both criteria:

**Priority Score = 50% Relative TB Burden + 50% Relative TB Incidence**

The score is an analytical framework developed for this portfolio case study and is not an official WHO prioritization methodology.

### Resource Alignment

Reported TB program budget and expenditure data were analyzed over the common **2018–2024** reporting period.

Country-level utilization comparisons were limited to high-burden countries with complete financial reporting across the analysis period. Countries with incomplete expenditure reporting were excluded from the utilization ranking to improve comparability.

---

## Tools & Skills Demonstrated

- **Python** — data preparation, cleaning, validation, and exploratory analysis
- **MySQL** — structured querying and business analysis
- **Power BI** — data modeling, DAX measures, interactive visualization, and analytical insights
- **Data Modeling** — dimensional modeling and relationships across surveillance and financial datasets
- **Data Validation** — aggregation checks, reporting-completeness assessment, and validation of analytical outputs
- **Business Intelligence** — translating complex public-health data into decision-oriented insights
- **Data Visualization & Storytelling** — connecting disease burden, prioritization, and resource utilization in an executive-level analytical narrative

---

## Data Source

This project uses publicly available **World Health Organization (WHO) Global Tuberculosis Programme** surveillance and program data.

The analysis combines TB burden, incidence, budget, expenditure, and related reporting information for the purposes of this independent Business Intelligence portfolio case study.

WHO is the original source of the underlying public data. The analytical framework, calculations, visualizations, and interpretations presented in this project were developed independently for this portfolio analysis.

---

## AI-Assisted Workflow

AI tools were used as a collaborative resource during the project to support **ideation, troubleshooting, analytical discussion, workflow refinement, and presentation development**.

The analytical approach remained human-led, including decisions regarding data preparation, business questions, analytical methodology, validation, interpretation, and final presentation of the findings.

---

## Project Purpose

This project was developed as a **Business Intelligence portfolio case study** demonstrating how public-health data can be transformed into structured analysis and decision-oriented insights through an end-to-end analytics workflow.

**WHO Data → Python: Prep & Validation → MySQL: Analysis → Power BI: Modeling & Insights**
