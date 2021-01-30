# FDI-Data-analsysis
Data analysis of FDI (Foreign Direct Investment) data using Tableau

# Dataset
The dataset consists of FDI (Foreign Direct Investment) information on various sectors (62 different sectors) for each year from financial year 2000 to 2016.
The dataset used can be found in this repo. It is named FDI Case Study.xls

# Objective
The aim of this project is to use the power of tableau for data analysis and to create impressive visualisations. The FDI dataset is first treated to various data cleaning processes after which we infer useful information by comparing different features. The final dashboards can be found in this repo under the file names - FDI_Project and FDI_Project2.

In this project we perform the following processes:
1. Import Data (Using tableau's Data Interpreter)
2. Unpivoting data from converting wide format to long format (using pivot option, as long format is better for data analysis)
3. Cleaning Labels (calculated fields to name the columns properly (LEFT([year],4)) ) 
4. Move to sheet for visualization creation
5. Find the highest value for FDI and its sector in latest year
6. Find the lowest Value of FDI and its sector in latest year
7. Get the trend of overall foreign direct investment(filter to select any indivual sector) (line chart, convert financial year data type to date)
8. Grouping of Sectors for comparison (Created gropus - Agriculture, Transport, Chemicals, Energy, Textile, Construction, Processing)
9. FDI in top 5 sectors (using filter - top 5 searches from FDI)
10. Sectors that reported high growth in FDI in last 5 years (Plotting sector vs financial year and using quick table calculation - Year Over Year Growth. File is uploaded as FDI_Project3)
11. Sectors that reported high decline in FDI in last 5 years
12. Which sectors has most varition in FDIs (plotting FDI and sector using box and whiskers, this is added i the final dashboard using dynamic filters)
13. Proportion of Each sector in FDI (Using FDI information information in highlight tables)
14. Find specific clusters that are present (Using Analyitics - Clusters, we found 11 suggested clusters)
15. Forecast for next year - (Using Analyitics - Forecast and trend lines)

The final dashboards can be found in this repo under the file names - FDI_Project and FDI_Project2.
