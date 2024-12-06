Analysis of NYC OpenData-NYC Free Tax Prep Sites — 01/2024 to 12/2024

This repository contains data, analytic code, and findings that support portions of the article, “NYC Provides Free Tax Prep to Residents,” published Month Date, Year. Please read that article, which contains important context and details, before proceeding.

Data

This analysis uses TKTKTK spreadsheets.

The spreadsheets come from the following sources:

Name of source: NYC OpenData
NYC_Free_Tax_Prep_Sites.csv: Raw data of Free Tax Prep Sites in NYC
Each of the spreadsheets contain, among others, the following columns relevant to the analysis:

Provider Name — Such as Food Bank for New York City or NYC Tax Prep-A-Thon. 
Building, Street, Unit columns — Provide the address for each location.
Borough- States the borough of each location. 
Phone- Includes the phonen number of most locations. 

Methodology

The notebook Data_Final_Draft.ipynb performs the following analyses:

Part 1: Scraping of website

The first step I did was to scrape the website. Not only did I came to find that I needed an API key but that there is no need to scrape the website.

Part 2: Instead of uploading CSV to analyze data, I extracted the data from the website. Then, I was able to to see how many free tax sites are per borough,
which providers own most of the sites and how many are active and unactive. Only two sites are unactive. Then, 

I was able to create a bar chart to visually see where the majority of the sites are located, which they are in Brooklyn. Followed by Manhattan, then the Bronx, Queens and last Staten Island. 

Outputs
The notebooks output this spreadsheet which contains a bar chart of number of tax prep sites in NYC by borough: output/tax_prep_sites.png.

Running the analysis yourself

You can run the analysis yourself. To do so, you'll need the following installed on your computer:

Python 3
The Python libraries specified in requirements.txt
Licensing

All code in this repository is available under the MIT License. The data file in the output/ directory is available under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. All files in the data/ directory are released into the public domain.

Feedback / Questions?

Contact Diana Escamilla Fuentes at your.d.escamillafuentes@journalism.cuny.edu.
