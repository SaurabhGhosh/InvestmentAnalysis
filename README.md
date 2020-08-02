# InvestmentAnalysis
## Abstract
Spark Funds is an asset management company. It wants to understand the global trends in investments to
aid in decision making.
Strategy of investment is to identify where most investments are happening and invest in that area.
It has two constraints – it wants to invest between 5 to 15 million USD and it wants to invest in country
where English is an official language.
To identify where to invest, the analysis outcome should clearly state the below information –
1. Which type of funding has received most investments within the said constraints. Type of funding to be
analysed are venture, seed, angel and private equity.
2. Which are to top 9 countries where most investments have been made considering the constraints and
which are the top 3 English speaking countries among these.
3. What are the top 3 sectors in those countries where most investments have been made.

## Approach and method

### 1. Data collection
- Companies - Details about the companies
- Rounds2 - Details about investments to the companies.

### 2. Data cleaning
- Cleaning of special characters from company identifier in Companies and Rounds2 data.
- Impute the blank investment amounts with zero.

### 3. Data preparation
- Merge of companies and rounds2 data to get company details added with the investment details
- Master data is created

### Data analysis
- Check which **investment type received largest average investment** within the constraint of Spark Funds (amount within 5 million USD and 15 million USD)

### Data analysis
- Check which are the top 9 countries for the selected investment type
- Check which are the **top 3 English speaking countries**

### Data collection
- Mapping Mapping of main sectors for company category.

### Data cleaning
- Clean the zero’s in category names in the mapping data.

### Data preparation
- Prepare the category names in master and mapping data for attaching the main sector with the master data.
- Prepare the data of top 3 sectors for the top 3 English speaking countries.

### Data analysis
- Check what are the company names for the top sectors in each of the three top countries based on investment received.

### Presentation
- The comparative investment amount and fraction of total investments for the seed, venture and private equity type of investments
- Top 9 countries and investments in them.

### Presentation
- Top 3 countries and the top 3 sectors in one view to present a better perspective


## Analysis - Investment Type
### Objective
The first analysis on the available data is carried out to find out which investment type is most suitable for
Spark Funds.
### Constraints
1. Investment between 5 million and 15 million USD
2. Investment to be made only in a country with English as one official language
3. Type of investment can be one of venture, angel, seed, private equity
### Analysis
Among the four investment types, considering the constraints, Venture type of investment is most suitable
for Spark Funds. Please refer Table 2.1 for details.

## Analysis - Country
### Objective
To find out the top 3 countries where English is an official language and has seen most investment amount
for Venture investment type.
### Analysis
- Country with most investment amount : United States of America
- Country with 2nd most investment amount : United Kingdom
- Country with 3rd most investment amount : India

## Analysis - Sector
### Objective
1. To find out the top 3 sectors for each of the top 3 countries
2. To find out the companies in top 2 sectors those received most investments
### Analysis
Questions | United States of America | United Kingdom | India
----------|--------------------------|----------------|------
Top Sector name (no. of investment-wise) | Others | Others | Others
Second Sector name (no. of investment-wise) | Social, Finance,
Analytics, Advertising | Social, Finance, Analytics, Advertising | Social, Finance, Analytics, Advertising
Third Sector name (no. of investment-wise) | Cleantech / Semiconductors | Cleantech / Semiconductors | News, Search and Messaging
For point 3 (top sector count-wise), which company received the highest investment? | Virtustream | Electric Cloud | FirstCry.com
For point 4 (second best sector count-wise), which company received the highest investment? | SST Inc. (Formerly ShotSpotter) | Celltick Technologies | Manthan Systems

## View – Investment Type
![Image of investment type](https://user-images.githubusercontent.com/10557638/89112493-57e59e80-d45b-11ea-8d84-b91a8746427f.PNG)

## View - Country
![Image of view country](https://user-images.githubusercontent.com/10557638/89112494-587e3500-d45b-11ea-9432-51b45d025ad8.PNG)

## View - Sector
![Image of view sector](https://user-images.githubusercontent.com/10557638/89112495-5916cb80-d45b-11ea-91bb-2be010a7182a.PNG)

## Conclusions
Based on the analysis and the views, Spark Funds can choose to invest in Venture type of investments,
preferably in USA, United Kingdom or India. The primary sectors of investments can be among
- Others
- Social, Finance, Analytics, Advertising
- Cleantech / Semiconductors for USA and United Kingdom
- News, Search and Messaging for India
