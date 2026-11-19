# DataCentersVACapstone
The goal of this project is to compare data centers and water in Virginia. Specifically, how data centers that will require groundwater permits compare to drinking water permits, drought status, and groundwater management areas. 

My research question is: What impact will data centers have on available drinking water and who will be impacted? 

The Piedmonet Environmental Council's publicly available proposed and active data center list will be used to catalogue data centers throughout the state. 
US Census data will be used to determine socioeconomic factors by county. 
The 2025 Annual Water Resources Report by Virginia's Department of Environmental Quality will be used for pumpage and water resource data.
DEQ and ODW maps of drought status and ground water management areas will be used for comparison to data center locations. 
If available, a comparison of permitted capacity and permit status for data centers and permits for drinking water across the sate will be compared. 


Data organization will be: 
```
drinking_water_data_centers
  raw_data
    water_data_raw
    census_data_raw
    data_center_data_raw
  clean_data
     water_data_clean 
     census_data_clean
     data_center_data_clean
  scripts
    data_cleaning
    figure_creation
    analysis_writing
    map_creation
  outputs
    figures
    analysis
    maps
  archive
```
