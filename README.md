# Bureau of Prisons API

I started to create a scraper for statistics section of BOP's website, but then after some exploration I managed to dig up some of the bop.gov's API endpoints.


Quick Facts Enpoint:
--------------------

https://www.bop.gov/PublicInfo/execute/quickfacts?todo=query&output=json

The JSON response contains all of the following stats:

*Statistics for people in federal prisons*
+ Age
+ Citizenship
+ Ethnicity (Hispanic and Non-Hispanic)
+ "Gender"
+ Offenses
+ Prison Security Levels
+ Race
+ Restricted Housing
+ Sentences Imposed

*Population Statistics*
+ Number of people in BOP Custody
+ Number of people in privagely managed facilities
+ Number of people in other kinds of facilities

*Staff Statistics*
+ Staff Ethnicity/Race
+ Staff "Gender"


Location Endpoint:
------------------
[https://www.bop.gov/coronavirus/data/locations.json](https://www.bop.gov/PublicInfo/execute/locations?todo=query&output=json)

*Information about FOB Facilities*
+ Name
+ Address
+ Location Types (Institution, Regional Office, Residential Reentry Mangement)
+ Gender
+ Private Facility (T/F)
+ Security Level


Residential Reentry Facility (Halfway House) Endpoint (Depreceated):
------------------------------------------------------
https://www.bop.gov/coronavirus/data/additional.json

*Information for individual RRC facilities*
+ Name
+ Address
+ Bed Count (w/ male and female breakdown)


Corona Virus Endpoint (Depreceated):
----------------------
https://www.bop.gov/coronavirus/json/final.json

*Reported Corona Virus Stats by Facility:*
+ City
+ Inmate Deaths
+ Inmate Recoveries
+ Inmates Testing Positive
+ Staff Testing Positive
+ Staff Recoveries
+ Staff Death Amount

+ # Inmate
+ https://www.bop.gov/PublicInfo/execute/inmateloc?todo=query&output=json&nameFirst=Jeremy&nameLast=Hammond




https://www.reddit.com/r/socialistprogrammers/comments/3zij7s/undocumented_federal_bureau_of_prisons_api/


https://prisondb.github.io/bopapidocs.html


## News

https://www.bop.gov/PublicInfo/execute/news?todo=query&output=json

## Policy Search

https://www.bop.gov/PublicInfo/execute/policysearch?todo=query&output=json

## Jobs
https://www.bop.gov/PublicInfo/execute/jobs?todo=query&output=json

## Unknown

https://www.bop.gov/PublicInfo/execute/foiadoc?todo=query&output=json

https://www.bop.gov/PublicInfo/execute/forms?todo=query&output=json

https://www.bop.gov/PublicInfo/execute/rrc?todo=query&output=json
