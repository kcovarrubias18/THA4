# THA-4: Chinese Aid to Africa

## Research Question: Which countries in Africa recieve the most/least aid from China? 
- My research question focuses on Chinese aid commitments to the African continent. This dataset can be found here: [AidData](https://www.aiddata.org). AidData compiles Chinese aid commitments from 2000-2014. To add additional context to these commitments, I also used GDP Per Capita numbers by country from: [World Bank](https://data.worldbank.org).  
- The goal is to see which countries in Africa recieve aid and if there are any interesting patterns when these aid commitments are mapped. 
- Inferences will be made through a simple linear regression and descriptive statistics (see Python analysis) and through plot.ly (see chart below)
## Data Sources
| Name | Citation | Data Link | Notes |
|------|------|------|------|
|AidData_GlobalChineseOfficialFinanceDataset_v1.0| Dreher, A., Fuchs, A., Parks, B.C., Strange, A. M., & Tierney, M. J. (2017). Aid, China, and Growth: Evidence from a New Global Development Finance Dataset. AidData Working Paper #46. Williamsburg, VA: AidData.|[AidData](https://www.aiddata.org/data/chinese-global-official-finance-dataset)|NA|
|The World Bank|Dataset: World Development Indicators: GDP per capita (constant 2010 US$): World Bank, International Program Comparison Database [License](https://datacatalog.worldbank.org/pulbic-licenses#cc-by) |[World Development Indicators](https://databank.worldbank.org/data/source/world-development-indicators/preview/on) [World Bank Terms of Use](http://www.worldbank.org/en/about/legal/terms-of-use-for-datasets)|[Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)|

| Name | Description(from source) |
|------|------|
|AidData Geocoded Global Chinese Official Finance|This dataset tracks the known universe of overseas Chinese official finance between 2000-2014, capturing 4,373 records totaling $354.4 billion. The data includes both Chinese aid and non-concessional official financing.|
|World Bank: World Development Indicators - GDP per capita (constant 2010 US$)|The primary World Bank collection of development indicators, compiled from officially-recognized international sources. It presents the most current and accurate global development data available, and includes national, regional and global estimates|
## Data Dictionary
| Dataset | Variable Name | Detail |
|------|------|------|
|World Bank|unique_id|Concatenation (Year, Country Name)|
|World Bank|Year|Year of record|
|World Bank|Country Name|Country|
|World Bank|Country Code|World Bank 3 character code|
|World Bank|GDP per capita (constant 2010 US$)|GDP per capita is gross domestic product divided by midyear population. GDP is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in constant 2010 U.S. dollars.|
|AidData|Refer to 'Data Dictionary' Folder in Repository|Readme_GlobalChineseOfficialFinanceDataset_v1.0.pdf|
## Plot.ly Analysis
[Link to Analysis](https://plot.ly/~Ryannnnnnnnn/22/)
<div>
    <a href="https://plot.ly/~Ryannnnnnnnn/22/?share_key=d8rd2shBmbzPMpJTvCjhyB" target="_blank" title="Plot 22" style="display: block; text-align: center;"><img src="https://plot.ly/~Ryannnnnnnnn/22.png?share_key=d8rd2shBmbzPMpJTvCjhyB" alt="Plot 22" style="max-width: 100%;width: 600px;"  width="600" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="Ryannnnnnnnn:22" sharekey-plotly="d8rd2shBmbzPMpJTvCjhyB" src="https://plot.ly/embed.js" async></script>
</div>


