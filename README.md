# SF_Real_Estate_Live
The final live version of the Real Estate Project.

The contents include the following:

data - a data directory
- SF-SFR-Sales-Final1.csv - The raw data downloaded from the SF MLS for all single-family home sales in SF 2009-2018.
- Realtor Neighborhoods.geojson - The mapping data downloaded from https://data.sfgov.org/Geographic-Locations-and-Boundaries/Realtor-Neighborhoods/5gzd-g9ns
- 2018MedianHomes-Final.csv - The median home prices scraped from the NAR Median Sales Price of Existing SFH for MSAs. https://www.nar.realtor/sites/default/files/documents/metro-home-prices-q2-2019-single-family-2019-08-07.pdf
- RankedTechIncome.csv - The Bureau of Labor Statistics - Occupational Employment Statistics income data for 2018 by MSA.  https://www.bls.gov/oes
- neighborhood_data.csv - A test dataset to use if you want to skip the data cleaning steps.

Colab Notebooks

- SF_Map_Code_Final.ipynb - The colab mapping code for the interactive SF Real Estate Map.
- Tech_Salary_vs_Housing_Cost.ipynb - The colab graphing code for the two graphs.

Heroku Files

- SF_Real_Estate_Project.py - Final executable python code from SF_Map_Code_Final.ipynb
- Procfile
- requirements.txt.
