# STA210 Final Course Project

# project description

We are interested in exploring the disparities in parks based on geographic areas, high/low income areas, and neighborhoods mostly of color or white. In our project, we analyzed data collected from Trust for Public Land to figure out how different amenities affect the overall quality of parks. After cross vaildation and checking r-squared/adjust r-squared/AIC/BIC, we selected a linear regression model which can predict total points (overall quality) of a park by data related to the numbers of dog parks, restrooms, playgrounds and splash grounds of the park. All analysis is conducted with R.

# data dictionary

## Provenance 

The provenance of original data is [The Trust for Public Land](https://www.tpl.org/parks-and-an-equitable-recovery-parkscore-report). 

## Data Dictionary: `parks.csv`

|variable                  |description |
|:-------------------------|:-----------|
|year                      | Year of measurement |
|rank                      | Yearly rank |
|city                      | City Name |
|med_park_size_data        | Median park size acres |
|med_park_size_points      | Median park size in points |
|park_pct_city_data        | Parkland as percentage of city area |
|park_pct_city_points      | Parkland as % of city area points |
|pct_near_park_data        | Percent of residents within a 10 minute walk to park |
|pct_near_park_points      | Percent of residents within a 10 minute walk to park points |
|spend_per_resident_data   | Spending per resident in USD |
|spend_per_resident_points | Spending per resident in points |
|basketball_data           | Basketball hoops per 10,000 residents |
|basketball_points         | Basketball hoops per 10,000 residents points |
|dogpark_data              | Dog parks per 100,000 residents|
|dogpark_points            | Dog parks per 100,000 residents points |
|playground_data           | Playgrounds per 10,000 residents |
|playground_points         | Playgrounds per 10,000 residents points |
|rec_sr_data               | Recreation and senior centers per 20,000 residents |
|rec_sr_points             | Recreation and senior centers per 20,000 residents points |
|restroom_data             | Restrooms per 10,000 residents |
|restroom_points           | Restrooms per 10,000 residents points |
|splashground_data         | Splashgrounds and splashpads per 100,000 residents |
|splashground_points       | Splashgrounds and splashpads per 100,000 residents points |
|amenities_points          | Amenities points total (ie play areas) |
|total_points              | Total points (varies in denominator per/year) |
|total_pct                 | Total points as a percentage|
|city_dup                  | City duplicated name |
|park_benches              | Number of park benches|
