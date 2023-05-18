# HealthCare_Project1
Project 1 - Healthcare Data

![image](https://github.com/deku1261/HealthCare_Project1/assets/129018366/eafea8d1-549e-48df-8da7-d955bb00966c)

<p align="center"> Covid 19 Vaccination Data</p>

<p class = indent>How our healthcare system responds to a crisis is important in ensuring that providers are making the most informed decisions about a patient's care. The data used in predictive analytics during the Covid crisis were used to make models that helped determine where the disease was occurring and what national policy was neccessary to combat the phenomenon. The dataset used in this analysis evaluates the overall covid-19 vaccine administration and vaccine equity at the county level giving us a better idea of certain vaccination metrics of each state within the U.S. throughout the entirety of the pandemic. 
  
<p class = indent>In the years recorded there is a noticeable increasing trend for "completeness percentage" for every state. The main goal of this project is to analyze and visualize data relating to a measure of completion percentage ('Completeness_pct') for each state over the last several years of the pandemic. Considering that vaccines weren't available until December of 2020, it explains why percentages of the "top 10" and "bottom 10" states in the U.S. show an increasing trend at such a rapid rate. The "Average Completed Dose Percentage" on the chart represents the proportion of people with a completed primary series whose Federal Information Processing Standards (FIPS) code is reported and matches a valid county FIPS code in the jurisdiction as described in the data set.     
 
># First Step was Cleaning the Data:
 >The 'Date' column was used to create a 'Year' column. This was accomplished by slicing the first four characters from each entry in the 'Date' column. 
  
># Code Snippet
>clean_df['Year'] = clean_df['Date'].str[:4]

>years = clean_df['Year'].unique()

># Second Step was Creating Visualizations:
 >Subplots were created for each unique year in the dataset. Each subplot is a bar plot showing the top 10 and bottom 10 states in terms of completion percentage for that year. The top 10 states are represented in green, while the bottom 10 states are represented in blue.
  
 ![bars](https://github.com/deku1261/HealthCare_Project1/assets/129018366/59972c6c-adc7-4cd4-93eb-1ed9d51d48a9)

>A final box plot was created to show the distribution of 'Completeness_pct' by year, post-cleaning. This allows us to easily see the central tendency and spread of the completion percentage over different years.
  
 ![boxes](https://github.com/deku1261/HealthCare_Project1/assets/129018366/ad9997de-752f-4159-ad58-4f0fc9af6af3)
