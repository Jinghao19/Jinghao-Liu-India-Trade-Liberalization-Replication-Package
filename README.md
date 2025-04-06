# Jinghao-Liu-India-Trade-Liberalization-Replication-Package
The replication package for Jinghao Liu's "The Impact of Trade Liberalization on Agricultural Productivity and Structural Transformation in India", intended for ECO1060 at University of Toronto

"Jinghao Liu - Replication Package\calibration\calibration_new.ipynb" - Jupyter notebook for structural estimation and counterfactual exercises

"Jinghao Liu - Replication Package\script" - Folder for STATA do files that extract data, clean data, and run reduced-form regression
 - globals.do - set up global path, need to customized to local environment
 - extract_ICRISAT.do - extract ICRISAT data from Excel into STATA
 - agri_prod_yield.do - generate agricultural productivity and other related variables from ICRISAT data
 - distid_91_11.do - clean 1991 census data and construct tariff exposure
 - distid_11.do - clean 2011 census data and merge with 1991 census data
 - concorde_ICRISAT.do - match districts in ICRISAT data to the census
 - merge_ICRISAT.do - merge ICRISAT data with census data based on harmonized districts and prepare variables for regression
 - shiftshare_ICRISAT.do - run the main reduced-form shift-share regression in the paper for Tables 2 and 3
 - sum stats.do - generate summary statistics for Table 1
 - map creating.do - generate maps for Figures 2,3,4

"Jinghao Liu - Replication Package\script" - Folder for STATA datasets
 - ICRISAT.dta - Raw ICRISAT data stored in STATA form
 - ICRISAT_raw.dta - Raw ICRISAT data after data construction for agricultural productivity
 - ICRISAT_balance.dta - ICRISAT data with agricultural productivity and with a balanced panel - not used since the panel is later balanced again for 1991 and 2011
 - 1991_aggregate.dta - 1991 census data in aggregate sectors
 - distid_1991_2011.dta - ID for each district after concordance for 1991 and 2011 census
 - merge_distid_1991_raw.dta - 1991 census data after variable transformation without tariff exposure variables
 - final industry-level tariff.dta - tariff change data at the industry level by Topalova
 - merge_distid_1991.dta - 1991 census data after variable transformation with tariff exposure variables
 - 2011_aggregate.dta - 2011 census data in aggregate sectors
 - merge_distid_2011_raw.dta - 2011 census data after variable transformation without tariff exposure variables
 - merged_1991_2011.dta - merged dataset for 1991 and 2011 census data with tariff exposure variables
 - distid_ICRISAT.dta - ID for each district after concordance for ICRISAT and census
 - merged_ICRISAT.dta- merged main dataset for census and ICRISAT data

"Jinghao Liu - Replication Package\map" - Folder for shapefiles and STATA datasets for creating maps

"Jinghao Liu - Replication Package\raw data" - Folder for raw data for ICRISAT in Excel files

