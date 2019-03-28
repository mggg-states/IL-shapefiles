# Chicago Election Shapefile
This shapefile was obtained from the City of Chicago Data Portal and processed by members of the Metric Geometry and Gerrymandering Group (MGGG). 

## Sources
The precinct shapefile was obtained from the City of Chicago Data Portal (available here https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Precincts-current-/uvpq-qeeq). Demographic data was downloaded from the 2010 Decennial Census at the block level and from the 2013-2017 American Community Survey five-year estimates at the block group level, both from American FactFinder (https://factfinder.census.gov/faces/nav/jsf/pages/index.xhtml). Election results come from the Chicago Board of Election Commissioners website (https://chicagoelections.com/en/home.html). 

## Processing
Demographic data was aggregated from the block and block group levels to the precinct level using MGGG’s proration and roundoff tools (available here https://github.com/mggg/maup).

## Metadata
- `full_text`: Ward and precinct IDs
- `precinct`: Precinct ID
- `ward`: Ward ID
- `shape_area`: Precinct area in square feet
- `shape_len`: Precinct perimeter in feet
- `TOTPOP`: Total population from 2010 census
- `NH_WHITE`: Non-hispanic White population from 2010 census
- `NH_BLACK`: Non-hispanic Black population from 2010 census
- `NH_AMIN`: Non-hispanic American Indian and Alaska Native population from 2010 census
- `NH_ASIAN`: Non-hispanic Asian population from 2010 census
- `NH_NHPI`: Non-hispanic Native Hawaiian and Pacific Islander population from 2010 census
- `NH_OTHER`: Non-hispanic population of other race from 2010 census
- `NH_2MORE`: Non-hispanic population of two or more races from 2010 census
- `HISP`: Hispanic population from 2010 census
- `H_WHITE`: Hispanic White population from 2010 census
- `H_BLACK`: Hispanic Black population from 2010 census
- `H_AMIN`: Hispanic American Indian and Alaska Native population from 2010 census
- `H_ASIAN`: Hispanic Asian population from 2010 census
- `H_NHPI`: Hispanic Native Hawaiian and Pacific Islander population from 2010 census
- `H_OTHER`: Hispanic population of other race from 2010 census
- `H_2MORE`: Hispanic population of two or more races from 2010 census
- `VAP`: Voting age population from 2010 census
- `HVAP`: Hispanic voting age population from 2010 census
- `WVAP`: White voting age population from 2010 census
- `BVAP`: Black voting age population from 2010 census
- `AMINVAP`: American Indian and Alaska Native voting age population from 2010 census
- `ASIANVAP`: Asian voting age population from 2010 census
- `NHPIVAP`: Native Hawaiian and Pacific Islander voting age population from 2010 census
- `OTHERVAP`: Voting age population of other race from 2010 census
- `2MOREVAP`: Voting age population of two or more races from 2010 census
- `TOTHH`: Total number of households from 2013-2017 ACS
- `LESS_10K`: Number of households with income for past 12 months under $10,000 from 2013-2017 ACS
- `10K_15K`: Number of households with income for past 12 months between $10,000 and $14,999 from 2013-2017 ACS
- `15K_20K`: Number of households with income for past 12 months between $15,000 and $19,999 from 2013-2017 ACS
- `20K_25K`: Number of households with income for past 12 months between $20,000 and $24,999 from 2013-2017 ACS
- `25K_30K`: Number of households with income for past 12 months between $25,000 and $29,999 from 2013-2017 ACS
- `30K_35K`: Number of households with income for past 12 months between $30,000 and $34,999 from 2013-2017 ACS
- `35K_40K`: Number of households with income for past 12 months between $35,000 and $39,999 from 2013-2017 ACS
- `40K_45K`: Number of households with income for past 12 months between $40,000 and $44,999 from 2013-2017 ACS
- `45K_50K`: Number of households with income for past 12 months between $45,000 and $49,999 from 2013-2017 ACS
- `50K_60K`: Number of households with income for past 12 months between $50,000 and $59,999 from 2013-2017 ACS
- `60K_75K`: Number of households with income for past 12 months between $60,000 and $74,999 from 2013-2017 ACS
- `75K_100K`: Number of households with income for past 12 months between $75,000 and $99,999 from 2013-2017 ACS
- `100K_125K`: Number of households with income for past 12 months between $100,000 and $124,999 from 2013-2017 ACS
- `125K_150K`: Number of households with income for past 12 months between $125,000 and $149,999 from 2013-2017 ACS
- `150K_200K`: Number of households with income for past 12 months between $150,000 and $199,999 from 2013-2017 ACS
- `200K_MORE`: Number of households with income for past 12 months over $200,000 from 2013-2017 ACS
- `JOINID`: Unique ID
- `Emanuel_M1`: Number of votes for Rahm Emanuel in 2015 mayoral general election
- `Wilson_M15`: Number of votes for Willie Wilson in 2015 mayoral general election
- `Fioretti_M`: Number of votes for Robert Fioretti in 2015 mayoral general election
- `Garcia_M15`: Number of votes for Jesus “Chuy” Garcia in 2015 mayoral general election
- `Walls_M15`: Number of votes for William Walls in 2015 mayoral general election
