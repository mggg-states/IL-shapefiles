# Chicago Election Shapefile
This shapefile was obtained from the City of Chicago Data Portal and processed by members of the Metric Geometry and Gerrymandering Group (MGGG). 

## Sources
The precinct shapefile was obtained from the [City of Chicago Data Portal](https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Precincts-current-/uvpq-qeeq). Demographic data were downloaded from the 2010 Decennial Census at the block level and from the 2013-2017 American Community Survey (ACS) five-year estimates at the block group level, both from [American FactFinder](https://factfinder.census.gov/faces/nav/jsf/pages/index.xhtml). Demographic data estimates at the block group level for the 2015-2019 ACS, along with additional 2010 Decennial Census data at the block level, were downloaded from the [National Historic GIS](https://data2.nhgis.org/main#). Election results come from the [Chicago Board of Election Commissioners website](https://chicagoelections.com/en/home.html). 

## Processing
Demographic data were disaggregated from block groups to blocks and aggregated from the block and block group levels to the precinct level using [MGGG’s proration and roundoff tools](https://github.com/mggg/maup). For 2015-2019 population estimates, block group data were weighted by 2010 Census block population for the disaggregation process.

## Metadata
- `full_text`: Ward and precinct IDs
- `precinct`: Precinct ID
- `ward`: Ward ID
- `ward_prec`: Alternate code for Ward and precinct IDs
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
- `H_AMIN`: HispaEmanuel_M1nic American Indian and Alaska Native population from 2010 census
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
- `TOTV_19`: Number of votes cast in the 2019 mayoral general election
- `JOYCE_19`: Number of votes for Jerry Joyce in 2019 mayoral general election
- `VALLAS_19`: Number of votes for Paul Vallas in 2019 mayoral general election
- `WILSON_19`: Number of votes for Willie Wilson in 2019 mayoral general election
- `PRECK_19`: Number of votes for Toni Preckwinkle in 2019 mayoral general election
- `DALEY_19`: Number of votes for Bill Daley in 2019 mayoral general election
- `MCCART_19`: Number of votes for Gary McCarthy in 2019 mayoral general election
- `CHICO_19`: Number of votes for Gery Chico in 2019 mayoral general election
- `MEND_19`: Number of votes for Susana Mendoza in 2019 mayoral general election
- `ENYIA_19`: Number of votes for Amara Enyia in 2019 mayoral general election
- `FORD_19`: Number of votes for La Shawn Ford in 2019 mayoral general election
- `SALGRIF_19`: Number of votes for Neal Sales-Griffin in 2019 mayoral general election
- `LHGTFT_19`: Number of votes for Lori Lightfoot in 2019 mayoral general election
- `FIORETTI_1`: Number of votes for Bob Fioretti in 2019 mayoral general election
- `KOZLAR_19`: Number of votes for John Kozlar in 2019 mayoral general election
- `TOTV_RO15`: Number of votes cast in the 2015 mayoral runoff election
- `RO_E15`: Number of votes for Rahm Emanuel in 2015 mayoral runoff election
- `RO_G15`: Number of votes for Jesus “Chuy” Garcia in 2015 mayoral runoff election
- `TOTV_G15`: Number of votes cast in the 2015 mayoral general election
- `EMAN_G15`: Number of votes for Rahm Emanuel in 2015 mayoral general election
- `WILS_G15`: Number of votes for Willie Wilson in 2015 mayoral general election
- `FIORET_G15`: Number of votes for Robert Fioretti in 2015 mayoral general election
- `GARCIA_G15`: Number of votes for Jesus “Chuy” Garcia in 2015 mayoral general election
- `WALLS_G15`: Number of votes for William Walls in 2015 mayoral general election
- `TOTPOP19`: Total population from 2015-2019 ACS
- `NH_WHITE19`: Non-hispanic White population from 2015-2019 ACS
- `NH_BLACK19`: Non-hispanic Black population from 2015-2019 ACS
- `NH_AMIN19`: Non-hispanic American Indian and Alaska Native population from 2015-2019 ACS
- `NH_ASIAN19`: Non-hispanic Asian population from 2015-2019 ACS
- `NH_NHPI19`: Non-hispanic Native Hawaiian and Pacific Islander population from 2015-2019 ACS
- `NH_OTHER19`: Non-hispanic population of other race from 2015-2019 ACS
- `NH_2MORE19`: Non-hispanic population of two or more races from 2015-2019 ACS
- `HISP19`: Hispanic population from 2015-2019 ACS
- `H_WHITE19`: Hispanic White population from 2015-2019 ACS
- `H_BLACK19`: Hispanic Black population from 2015-2019 ACS
- `H_AMIN19`: Hispanic American Indian and Alaska Native population from 2015-2019 ACS
- `H_ASIAN19`: Hispanic Asian population from 2015-2019 ACS
- `H_NHPI19`: Hispanic Native Hawaiian and Pacific Islander population from 2015-2019 ACS
- `H_OTHER19`: Hispanic population of other race from 2015-2019 ACS
- `H_2MORE19`: Hispanic population of two or more races from 2015-2019 ACS
- `MAY19LL`: Number of votes for Lori Lightfoot in 2019 mayoral runoff election
- `MAY19TP`: Number of votes for Toni Preckwinkle in 2019 mayoral runoff election

## Projection
This shapefile uses a UTM Zone 16N projection (EPSG 26916).
