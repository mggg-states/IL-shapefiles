# Chicago Election Shapefile
This shapefile was obtained from the City of Chicago Data Portal and processed by members of the Metric Geometry and Gerrymandering Group (MGGG). 

## Sources
The precinct shapefile was obtained from the City of Chicago Data Portal (available here https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Precincts-current-/uvpq-qeeq). Demographic data was downloaded from the 2010 Decennial Census at the block level and from the 2013-2017 American Community Survey five-year estimates at the block group level, both from American FactFinder (https://factfinder.census.gov/faces/nav/jsf/pages/index.xhtml). Election results come from the Chicago Board of Election Commissioners website (https://chicagoelections.com/en/home.html). 

## Processing
Demographic data was aggregated from the block and block group levels to the precinct level using MGGG’s proration and roundoff tools (available here https://github.com/gerrymandr/Preprocessing).

## Metadata
- `full_text`: Ward and precinct IDs
- `TOTPOP`: Total population from 2010 census
- `HISP`: Hispanic population from 2010 census
- `NH_WHITE`: Non-hispanic white population from 2010 census
- `NH_BLACK`: Non-hispanic black population from 2010 census
- `NH_AMIN`: Non-hispanic American Indian and Alaska Native population from 2010 census
- `NH_ASIAN`: Non-hispanic Asian population from 2010 census
- `NH_NHPI`: Non-hispanic Native Hawaiian and Pacific Islander population from 2010 census
- `NH_OTHER`: Non-hispanic population of other race from 2010 census
- `NH_2MORE`: Non-hispanic population of two or more races from 2010 census
- `VAP`: Voting age population from 2010 census
- `HVAP`: Hispanic voting age population from 2010 census
- `WVAP`: White voting age population from 2010 census
- `BVAP`: Black voting age population from 2010 census
- `AMINVAP`: American Indian and Alaska Native voting age population from 2010 census
- `ASIANVAP`: Asian voting age population from 2010 census
- `NHPIVAP`: Native Hawaiian and Pacific Islander voting age population from 2010 census
- `OTHVAP`: Voting age population of other race from 2010 census
- `X2MOREVAP`: Voting age population of two or more races from 2010 census
- `TOTPOP17`: Total population from 2013-2017 ACS
- `NH_WHITE17`: Non-hispanic white population from 2013-2017 ACS
- `NH_BLACK`: Non-hispanic black population from 2013-2017 ACS
- `NH_AMIN17`: Non-hispanic American Indian and Alaska Native population from 2013-2017 ACS
- `NH_NHPI17`: Non-hispanic Native Hawaiian and Pacific Islander population from 2013-2017 ACS
- `NH_OTHER17`: Non-hispanic population of other race from 2013-2017 ACS
- `NH_2MORE17`: Non-hispanic population of two or more races from 2013-2017 ACS
- `HISP17`: Hispanic population from 2013-2017 ACS
- `H_WHITE17`: Hispanic white population from 2013-2017 ACS
- `H_BLACK17`: Hispanic black population from 2013-2017 ACS
- `H_AMIN17`: Hispanic American Indian and Native Alaska population from 2013-2017 ACS
- `H_ASIAN17`: Hispanic Asian population from 2013-2017 ACS
- `H_NHPI17`: Hispanic Native Hawaiian and Pacific Islander population from 2013-2017 ACS
- `H_OTHER17`: Hispanic population of other race from 2013-2017 ACS
- `H_2MORE17`: Hispanic population of two or more races from 2013-2017 ACS
- `JOINID`: Unique identifier for precincts
- `WARD_1`: Ward ID
- `PRECINCT_1`: Precinct ID
- `Emanuel_M1`: Number of votes for Rahm Emanuel in 2015 mayoral race
- `Wilson_M15`: Number of votes for Willie Wilson in 2015 mayoral race
- `Fioretti_M`: Number of votes for Robert Fioretti in 2015 mayoral race
- `Garcia_M15`: Number of votes for Jesus “Chuy” Garcia in 2015 mayoral race
- `Walls_M15`: Number of votes for William Walls in 2015 mayoral race
