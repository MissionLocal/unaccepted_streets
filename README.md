# San Francisco's unaccepted streets

Here's the data behind our story [San Francisco’s forgotten roads: Bayview has 1/4 of city’s ‘unaccepted streets’](https://missionlocal.org/2025/07/sf-bayview-unaccepted-streets/)

`analysis.ipynb` contains our analysis of unaccepted streets data in San Francisco. 

`data` contains the raw data files: 
- `dpw_data.csv` contains the most up-to-date records of every unaccepted street in San Francisco, which are streets that have not been adopted as city or state roads. We obtained this dataset on July 10, 2025 via a records request. 
- `Streets___Active_and_Retired_20250709.csv` contains records on `all` streets data in San Francisco, including active and retired streets. The data was downloaded on July 9, 2025 from [S.F. Open Data](https://data.sfgov.org/Geographic-Locations-and-Boundaries/Streets-Active-and-Retired/3psu-pn9h/about_data). We used this data to georeference the unaccepted streets data from DPW. We did not use this data to determine which streets are unaccepted.
- `supe22.geojson` contains area polygons of each supervisor district in the city. The data was downloaded from [S.F. Open Data](https://data.sfgov.org/Geographic-Locations-and-Boundaries/Supervisor-Districts-2022-/f2zs-jevy/about_data).

  `output` contains our cleaned data files
  - `length_overview` contains a summary table with the length of unaccepted streets per district (and compared to the total length of streets in each district)
  - `output.geojson` contains the data we used for mapping (maps below).
 
For any questions, please email kelly@missionlocal.com
 
![image](https://newspack-missionlocal.s3.amazonaws.com/mission/wp-content/uploads/2025/07/district_10_mobile.png)

![image](https://newspack-missionlocal.s3.amazonaws.com/mission/wp-content/uploads/2025/07/sf.png)

