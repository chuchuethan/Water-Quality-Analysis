# :sweat_drops: Water-Quality-Analysis :sweat_drops:
An analysis of messy government data on different water sites and their attributes (pH, temperature, depth, salinity, etc.)

# Tools Used
- Excel pivot tables
- Excel power query
- PostGreSQL
- PowerPoint
- Tableau

# Goals
- Practice cleaning large and complex datasets to prepare them for analysis
- Practice SQL to extract insights from cleaned data
- Create a dashboard to visualize cleaned data

# Challenges
- Lack of context on the dataset:
  - Are S. Poe and Susan Poe the same person?
  - Are water sites "B" and "Bay" different?
- handling null values in quantitative fields:
  - What should we replace null values with in columns like pH, water_depth_m, etc.?
- Separating names of field tech reporters
  - Field tech reporters were recorded in a comma-separated fashion, so combined with cleaning the names themselves, it was challenging splitting up these fields by comma while also having to account for the fact that some names had spaces, periods, etc.

# Link to Tableau Dashboard
[Link](https://public.tableau.com/views/waterquality_17665457367980/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
