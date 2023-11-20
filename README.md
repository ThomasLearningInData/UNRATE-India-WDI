# World Development Indicators: Analysis of unemployment rate in India 
In this notebook, I leveraged the power of SQL within the Python environment to conduct a comprehensive analysis. By seamlessly integrating SQL queries into Python code, I harnessed the capabilities of both languages to explore and derive insights from the dataset.

### Goals
- Explore the WDI database to understand what type of data is presented in each table;
- Explore the unemployment rate dataset for India;
- Extract the related data from the selected indicators, and prepare for data cleaning and manipulation;
- Create data visualization on unemployment in India over time and compare the unemployment rate in different categories

### Dataset Information
The World Development Indicators (WDI) is the primary World Bank collection of development indicators, compiled from officially-recognized international sources. It presents the most current and accurate global development data available, and includes national, regional and global estimates.

The WDI from the World Bank contain over a thousand annual indicators of economic development from hundreds of countries around the world.

Datasets link: https://datacatalog.worldbank.org/search/dataset/0037712

| Table         | Total Rows | Total Columns |
| ------------- | ---------- | ------------- |
| Country       | 247        | 31            |
| CountryNotes  | 4857       | 3             |
| FootNotes     | 532415     | 4             |
| Indicators    | 5656458    | 6             |
| Series        | 1345       | 20            |
| SeriesNotes   | 369        | 3             |

### Key highlights
- The primary education has the highest unemployment rate
- Youth female with age 15-25 has higher unemployment rate compare to male.
- There is a great improvement for secondary and tertiary education in 2005. So we should do a case study in this year to find out which key factors helped India reduce unemployment.


