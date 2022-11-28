AC Reports and Recommendations Scraper.

First draft of UK Energy and AC Certificates 
target website to scrape: 
https://www.gov.uk/find-energy-certificate
api website used to import CEPC csv files: 
https://epc.opendatacommunities.org/non-domestic/search

ac_report_scraper.ipynd retrieves AC Reports  from a pre-established list of Zip (or Postal) codes we extracted from the api.
Use case for this script is to join CEPCs, AC Reports, and AC Recommendations databases even though the API will not let us access AC Reports and Recommendations data, hence an automated scraping from the User friendly website.

data folder contains: 
- 4 files downloaded from the api:
CEPC and CEPC Recommendations for both postal codes EC***** and WS***** (note: 5000 first entries)
- output.csv : our result database export.
