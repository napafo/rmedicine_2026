# DIVINE: Curated Datasets and Tools for Medical Data

DIVINE is an R package that provides 14 curated datasets and 6 data management functions to streamline medical research workflows. It helps researchers in access clean, structured data and perform essential tasks such as cleaning, summarizing, visualization, and exporting with minimal effort.

The datasets originate from a multicenter COVID-19 study conducted in 2020-2021 in the south metropolitan area of Barcelona (Spain), including data from 5813 patients across four pandemic waves. They contain information on baseline characteristics (e.g. demographics and comorbidities), follow-up during hospitalisation (e.g. intensive care unit admission and treatments received), and clinical outcomes (e.g. complications and in-hospital mortality).

The 6 functions included in DIVINE follow a data curation pipeline: data_overview() for data inspection, impute_missing() for handling missing values, multi_join() to merge datasets, stats_table() to create descriptive tables, multi_plot() for visualization (e.g., boxplots and histograms), and export_data() to export results to formats such as CSV and RDS.

The datasets have been made publicly available to support reproducible research and enable its reuse in research applications such as validating existing COVID-19 predictive models or studying outcome incidence and prognostic factors. They can also be used as a teaching resource in biostatistics, epidemiology, or data science courses.

The DIVINE package is available on CRAN and GitHub.
