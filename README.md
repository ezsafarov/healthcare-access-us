# healthcare-access-us

## 🏥 Introduction

This project uses a multivariate approach to explore healthcare access across more than 3,000 U.S. counties. By combining socioeconomic and environmental indicators such as median income, food insecurity, insurance coverage, and exercise access, a unified Healthcare Access Score was developed to assess disparities in care availability.

The analysis covers 2020–2024 and forms part of a broader portfolio exploring regional well-being across the United States. Key outputs include composite scoring, regression modeling, clustering, and interactive Tableau visualizations.

## 📊 Tableau Dashboard

An interactive Tableau dashboard was created to visualize the key outcomes of the analysis:

The link on tableau public: 
https://public.tableau.com/app/profile/emil.safarov/viz/HealthcareAccessinU_S_/HealthcareAccessinU_S?publish=yes

## 📄 Case Study

The full project analysis and narrative is documented in the following case study PDF:

🔗 [EmilSafarov_HealthcareAccess_CaseStudy.pdf](./case_study/EmilSafarov_HealthcareAccess_CaseStudy.pdf)

This case study walks through the end-to-end process, including:
- Research motivation and problem definition
- Data selection and preprocessing
- Composite score development
- Modeling approach (regression & clustering)
- Visual insights and final conclusions

> 📍 Located in the `/case_study/` folder



├── EmilSafarov_HealthcareAccess_CaseStudy.pdf #case explanation
├── LICENSE
├── README.md
├── data
│   ├── final #inputdatasets
│   ├── notes #data processing notes
│   ├── processed
│   └── raw
├── project_docs
│   ├── Healthcare Access in U.S..twbx  #tableau workbook
│   ├── Project_task_brief.pdf #project prompt
│   ├── Stakeholder_matrix.xlsx
│   └── TOR_Healthcare_Access_US_Counties.pdf
├── scripts 
│   ├── 1_data_cleaning
│   ├── 2_first_EDA.ipynb
│   ├── 3_sample_geo_visualization.ipynb
│   ├── 4_2nd_EDA_linear_regression.ipynb
│   ├── 5_clustering.ipynb
│   └── 6_sample_time_series.ipynb
└── visualization samples 
    ├── 2_EDA
    ├── 3_geo
    ├── 4_linear_regression
    ├── 5_clustering
    ├── 6_time_series
    └── Tableau_viz.pdf
