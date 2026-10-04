# CEP-64 EDAV Course Project — Adult Literacy

Open `index.html` in a browser.

Data files:
- original_literacy_data.csv — supplied source data
- q1_literacy_averages.csv — Q1
- q2_state_gender_filter.csv — Q2
- q3_missing_data_audit.csv — Q3
- q4_region_aggregation.csv — Q4
- q5_gender_gaps.csv — Q5

Methodology:
- Q3 found 0 missing values, so no original values were imputed.
- Q4 cannot produce multiple age-group comparisons because the supplied data has one adult age scope (15+) and no age-group column.
- Q4 region is a derived classification for aggregation and is explicitly labeled as such.
- Q5 gender gap = male literacy − female literacy.
