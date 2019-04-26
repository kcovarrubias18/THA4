# THA-4: Chinese Aid to Africa

## Research Question: Which countries in Africa recieve the most/least aid from China? 
- My research question focuses on Chinese aid commitments to the African continent. This dataset can be found here: [AidData](https://www.aiddata.org). AidData compiles Chinese aid commitments from 2000-2014. To add additional context to these commitments, I also used GDP Per Capita (PPP) numbers by country from: [World Bank](https://data.worldbank.org).  
- The goal is to see which countries in Africa recieve aid and if there are any interesting patterns when these aid commitments are mapped. 
- Inferences will be made through a simple linear regression and descriptive statistics (see Python analysis) and through plot.ly (see chart below)
## Data Sources
| Name | Citation | Data Link | Notes |
|------|------|------|------|
|AidData Geocoded Global Chinese Official Finance(v.1.0.1)| AidData Research and Evaluation Unit. 2017. Geocoding Methodology, Version 2.0. Williamsburg, VA: AidData at William & Mary. https://www.aiddata.org/publications/geocoding-methodology-version-2-0|[AidData](https://www.aiddata.org/data/geocoded-chinese-global-official-finance-dataset)|NA|
|The World Bank|Dataset: World Development Indicators: GDP per capita, PPP (constant 2011 international $): World Bank, International Program Comparison Database [License](https://datacatalog.worldbank.org/pulbic-licenses#cc-by) |[World Development Indicators](https://databank.worldbank.org/data/source/world-development-indicators/preview/on) [World Bank Terms of Use](http://www.worldbank.org/en/about/legal/terms-of-use-for-datasets)|[Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)|

| Name | Description(from source) |
|------|------|
|AidData Geocoded Global Chinese Official Finance|This dataset geolocates Chinese Government-financed projects that were implemented between 2000-2014. It captures 3,485 projects worth $273.6 billion in total official financing. The dataset includes both Chinese aid and non-concessional official financing.|
|World Bank: World Development Indicators - GDP per capita, PPP(constant 2011)|The primary World Bank collection of development indicators, compiled from officially-recognized international sources. It presents the most current and accurate global development data available, and includes national, regional and global estimates|
## Data Dictionary
| Dataset | Variable Name | Detail |
|------|------|------|
|World Bank|unique_id|Concatenation (Year, Country Name)|
|World Bank|Year|Year of record|
|World Bank|Country Name|Country|
|World Bank|Country Code|World Bank 3 character code|
|World Bank|GDP per capita, PPP (constant 2011 international $) [NY.GDP.PCAP.PP.KD]|GDP per capita based on purchasing power parity (PPP). PPP GDP is gross domestic product converted to international dollars using purchasing power parity rates. An international dollar has the same purchasing power over GDP as the U.S. dollar has in the United States. GDP at purchaser's prices is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in constant 2011 international dollars.|
## Plot.ly Analysis
<div>
    <a href="https://plot.ly/~Ryannnnnnnnn/4/?share_key=ttMywOuo3pHmQeSgOecqeR" target="_blank" title="Plot 4" style="display: block; text-align: center;"><img src="https://plot.ly/~Ryannnnnnnnn/4.png?share_key=ttMywOuo3pHmQeSgOecqeR" alt="Plot 4" style="max-width: 100%;width: 600px;"  width="600" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="Ryannnnnnnnn:4" sharekey-plotly="ttMywOuo3pHmQeSgOecqeR" src="https://plot.ly/embed.js" async></script>
</div>

[link to plot.ly analysis](https://plot.ly/~Ryannnnnnnnn/4/)
