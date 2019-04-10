# Major Metro Areas and Their Cities
Summary: CSV file with all the cities in the U.S. that fall into metro areas with total populations > 500,000. Created using U.S. Census data (2017 population projections).

**Context:**

Recently I needed to get a list of cities in the U.S. that fall within a "major" metropolitan area, and match them up with an internal list of cities. This proved to be surprisingly hard; free external sources had many data inconsistencies and other issues that made them difficult to work with. This was created by joining metro areas and their populations with the cities within those metro areas using CBSA code, joining state names using State FIPS code, and joining state abbreviations based on state name (because we don't use full state names). This is the resulting CSV that I went on to use for final processing.

**Columns:**
* CBSA Code (see the US Census website for info)
* State FIPS Code
* Metro Area Name
* City
* State
* Projected 2017 Population


