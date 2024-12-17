# A Data-Driven Approach to Politcal and Health Indicators on Maternal Mortality 
## Elisha Clark, Sarah Mathey, Katie Vana

### Description
Since the Dobbs v. Jackson Women's Health Organization decision was handed down by the US Supreme Court in 2022, the effect of access to abortion care on maternal mortality has become an increasingly salient topic. This paper asks whether there is a relationship between political indicators and maternal mortality rates when controlling for other predictive factors such as health indicator data. Moreover, we make the case for the necessity of continuing to collect accurate data on the issue to improve and expand this research.

### Files

#### Code
- **ballotpedia_state_leg_scraper.ipynb**: Scrapes Ballotpedia for state legislative election resluts 
- **create_main_regression_dataset.ipynb**: merges all intermediary datasets to create primary dataset for analysis
- **health_indicator_ag_script.ipynb**: merges all health indicator data files 
- **initial_regression_analysis.ipynb**: Regression analysis and confidence interval visualizations
- **maternal_mortality_county_data_wrangling.ipynb**: merges all maternal mortality data files and has some experimental data viz 
- **state_data_viz.Rmd**: Main source for map data visualization 

#### data
1. **processed**
- *map_state_data.csv*
- **maternal_mortality_complete_dataset.csv** *main analytical dataset*
- *maternal_mortality_country_all_race_all_ages_2019.csv*
- *merged_health_indicators.csv*
- *state_gov_control_2017.csv*
- *state_gov_control_2019.csv*

2. **raw**
- **cb_2018_us_state_20m**
- **IHME_USA_COD_COUNTY_RACE_ETHN_200_2019_MX_MATER_NEONATAL_FEMALE**
- *abortion_laws_index.csv*
- *house_leg_election_results.csv*
- *project_political_data - Center_for_repro_reights.csv*
- *project_political_data - gov_party.csv*
- *project_political_data - States.csv*
- *senate_leg_election_results.csv*

#### viz
Data visualizations generated in support of this work 

[Google Drive](https://drive.google.com/drive/u/1/folders/1VKmPn7mmTaHvDyF3V5ZUW3z9oejjiPNt)
