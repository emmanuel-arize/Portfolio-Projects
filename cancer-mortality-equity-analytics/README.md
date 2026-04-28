# Cancer Equity Dashboard: Saving 181,650 Lives Through Targeted Action

>  **Work in Progress**  
> This is an active, self-directed learning project focused on healthcare equity analytics. Core visualizations are functional, but the project is still under development. Documentation and methodology are being refined.

##  Overview

This dashboard combines two powerful analytical views to reveal where racial, geographic, and demographic disparities in cancer mortality are most severe — and where targeted interventions can save the most lives.

**Key Finding**: Using Non-Hispanic White mortality rates as the benchmark, we estimate that **181,650 cancer deaths** among non-White populations between 2017–2020 could have been prevented if equity in care and outcomes had existed.

---

## Key Metrics

| Metric | Value |
|--------|-------|
| **Total Lives That Could Be Saved** | 181,650 |
| **Excess Deaths** | 174,930 |
| **Average Racial Disparity Score** | 1.53 |
| **Benchmark** | Non-Hispanic White mortality rate |

*Disparity Score Interpretation: 1.53 means non-White groups experienced 53% higher cancer mortality than the benchmark on average.*

---

## Who Is Most Affected?

### By Race & Ethnicity
- **Non-Hispanic Black**: 81K excess deaths
- **Other/Multiracial**: 78K excess deaths  
- **American Indian/Alaska Native**: 22K excess deaths (highest disparity at **2.6×** benchmark)

### By Race & Sex
| Group | Disparity Score | Interpretation |
|-------|-----------------|----------------|
| American Indian/Alaska Native **Females** | 3.0 | 3× benchmark rate |
| American Indian/Alaska Native **Males** | 2.4 | 2.4× benchmark rate |
| Black/African American **Females** | 1.4 | 40% above benchmark |
| Asian/Pacific Islander **Females** | 0.9 | **Better** than benchmark  |

### By Age Group
- **75+ (Older Seniors)**: 91K excess deaths
- **45–64 (Older Adults)**: 35K excess deaths

### By Cancer Type
1. **Digestive cancers** (12.4K lives saved in Florida alone)
2. **Respiratory cancers**
3. **Reproductive cancers**
4. **Blood cancers**

---

##  Where Should We Focus?

### Top States for Intervention
| State | Cancer Type | Preventable Deaths |
|-------|-------------|-------------------|
| **Florida** | Digestive | 12.4K |
| **Florida** | Respiratory | 10.4K |
| **Florida** | Reproductive | 4.0K |
| **New York** | Respiratory | High priority |
| **Ohio** | Digestive | High priority |

### Intervention Priority Scores
- **Florida**: 0.60 (highest state-level need)
- **South Region**: 1.11 normalized priority score (most critical area for equity-focused investment)

---

## Actionable Insights

This dashboard doesn't just show disparities — it identifies **where**, **for whom**, and **how** to act:

 **Target high-burden states**: Florida, New York, Ohio show highest preventable death counts  
**Prioritize vulnerable populations**: Black, AI/AN, and Multiracial communities, especially men over 45  
 **Learn from success**: Asian/Pacific Islander communities show better-than-benchmark outcomes — investigate protective factors  
 **Allocate efficiently**: Use Intervention Priority Scores to maximize impact across regions and demographics

---

##  Methodology

**Benchmarking Approach**:  
Non-Hispanic White mortality rates serve as the reference standard. Excess deaths calculated as:  
`Excess Deaths = Observed Deaths − Expected Deaths (if benchmark rate applied)`

**Disparity Score**:  
`Group Mortality Rate ÷ White Mortality Rate`  
- Score > 1: Higher mortality than benchmark  
- Score < 1: Lower mortality than benchmark

**Decomposition Analysis**:  
Adapting Kitagawa/Oaxaca-style methods to attribute disparity contributions across:
- Race/ethnicity
- Geographic region and state
- Cancer site
- Age and sex

---

## Data & Tools

**Data Sources** (2017–2020):
- CDC WONDER: Multiple Cause of Death
- National Center for Health Statistics (NCHS)
- U.S. Census Bureau geographic files

**Tools**:
- Power BI Desktop (DAX, data modeling, interactive visualizations)
- Excel/Python (data preprocessing)

---

##  Current Development Status

| Component | Status |
|-----------|--------|
| Core dashboard visualizations |  In Progress |
| Disparity metrics & benchmarking |  In Progress|
| Geographic analysis | In Progress |
| Decomposition workflows |  In Progress |
| Methodology documentation |  In Progress |


---

## Important Note

> **Synthetic Data Disclaimer**: This project uses synthetic data for analytical demonstration and learning purposes. "Lives That Could Be Saved" estimates reflect preventable deaths if non-White populations experienced the same cancer mortality rates as Non-Hispanic Whites. Methods and visualizations are being developed to build skills in healthcare equity analytics and prescriptive decision-making.

---

## Learning Objectives

This project supports my preparation for research in healthcare operations and optimization by developing:
- Proficiency in healthcare disparity quantification
- Experience with benchmarking and decomposition methods
- Skills in translating population health data into intervention priorities
- Foundation for optimization-driven resource allocation models

---

## 📬 Contact & Collaboration

**Emmanuel Arize**  
📧 arize5.emmanuel@outlook.com  
🔗 [LinkedIn](https://www.linkedin.com/in/emmanuel-arize-277270134/)  
 [GitHub](https://github.com/emmanuel-arize)

*Feedback and collaboration welcome! This is a learning project, and I'm open to suggestions for improvement.*

---

*Last updated: April 2026*  
*Status: Active development*
