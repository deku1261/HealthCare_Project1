Malav:
# Healthcare_Project_1
<p align="center"> Covid 19 Vaccination Data</p>

<p class = indent>Vaccination data is imperative to the safety and well-being of populations. Understanding the role of data within the healthcare field will help paint a broader picture of healthcare. Inturn, pivotal decisions that are driven by data points help CDC, Centers for Disease Control and Prevention, control health policy. Vaccination coverage across U.S. denotes the credibility and integrity of the healthcare field. Though there is much debate about the efficacy of vaccinations, data can help triangulate a truth driven and evidence based approach towards vaccinating populations. This became even more pertinent as the threat of a virus was eminent beginning March of 2020. Mortality from Covid-19 virus statistics were excluded from the dataset, yet further investigation is necessary to test efficacy, and track prevention of deaths. </p> 

<p class = indent>The question first begins with what percentage of the population has their vaccination series completed. Based on the data, we can see that the average series completion percentage increases over time (Figure 1). During 2021, the collection of series completion began. Due to the dataset being extremely large, filtering the data over monthly and yearly time axis is beneficial. Monthly and yearly datapoints were filtered from the original dataset as averages. On average, 2021, 2022, and 2023 vaccination series completion percentages were 26.84%, 51.01%, and 53.93% respectively (Figure 2). </p>


![image](https://github.com/deku1261/HealthCare_Project1/assets/92231055/179e51f2-1bd3-4658-9066-2ff683cf4c7a)

Figure 1. Average Monthly Cov-19 Vaccination Series Completion %

![image](https://github.com/deku1261/HealthCare_Project1/assets/92231055/18773593-8e14-4955-971c-cceb9aac3897)

Figure 2. Average Yearly Cov-19 Vaccination Series Completion %


<b>Robert:<b/>

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

Ariel:

Distribution of COVID-19 Vaccination by Age Groups from 2021 to 2023: A Comparative Analysis
The COVID-19 pandemic has presented an unprecedented global health crisis, prompting the rapid development and deployment of vaccines. Vaccination campaigns play a pivotal role in curbing the transmission of the virus, protecting vulnerable individuals, and reducing the burden on healthcare systems. To assess the distribution of COVID-19 vaccination by age groups, data from the CDC were analyzed. The study population was divided into three age categories: 5 to 17, 18 to 64, and 65 and older. The percentage of individuals within each age group who had completed the series of the vaccine was calculated and compared. Analysis of the data revealed notable variations in vaccination coverage among the different age groups. Surprisingly, the age group 5 to 17 exhibited the highest vaccination percentage. This finding can be attributed to the prioritization of school-age children and adolescents in vaccination campaigns, aiming to safeguard educational settings and reduce the potential for virus transmission within this population. In contrast, the 65 and over age group demonstrated the lowest percentage of vaccinated individuals.


In 2021: 5 to 17 year olds who completed the series of vaccinations were 51% of the population while the 65 + was only 10%
![2021 Completed chart](https://github.com/deku1261/HealthCare_Project1/assets/126893877/d63750be-a015-436f-9403-558975cc5761)

In 2022: 5 to 17 year olds grew from 51% to 64% while the 65+ age group dropped from 10% to 7%
![2022 Completed chart](https://github.com/deku1261/HealthCare_Project1/assets/126893877/21c19692-c77e-4840-b3de-ec288fb9be12)

In 2023: there were no changes in the percentage although the number totals have drastically dropped.
![2023 Completed chart](https://github.com/deku1261/HealthCare_Project1/assets/126893877/62256239-21a3-4e2a-ae9c-7a2da7061215)

The overall for each of the age groups from year to year
![Year over Year chart](https://github.com/deku1261/HealthCare_Project1/assets/126893877/3421fcb1-1a94-4ebf-83a2-d7d4eca1d50f)
In September 2021 was the first round of Covid vaccinations so the data only shows 3 months of data.  Although at that time it was a rush to get as many people vaccinated as possible.  Mainly focusing on the school age group.  The 2022 which is the only data that shows a full 12-month period.  Finally the 2023 data shows the same percentage as 2022 but the number of people fully vaccinated dropped.  The factors may include that it is showing the tail end of the Vaccinations.  Only 5 months of data.



Rachel:

# HealthCare_Project1
![download](https://github.com/deku1261/HealthCare_Project1/assets/124642442/a9ad3656-dede-4ebd-94f9-279398118f06)

The COVID-19 pandemic has had a profound impact on public health and economies worldwide. As countries grapple with the challenges posed by the virus, the development and distribution of effective vaccines have emerged as crucial tools in controlling its spread. The United States of America, as one of the most affected nations, has played a significant role in the global vaccination effort. Data was acquired by the Centers for Disease Control and Prevention (CDC) regarding the COVID-19 vaccines administered in the United States. 


The distribution of COVID-19 vaccines plays a crucial role in achieving widespread immunization and controlling the spread of the virus. In this study, we examined data obtained from the Centers for Disease Control and Prevention (CDC) to investigate the vaccination rates in different regions of the United States. Our findings revealed a significant disparity between the metro and non-metro areas in terms of vaccine uptake. Utilizing a pie chart, we visualized the distribution of vaccinated individuals, with 45.5% residing in metro regions and 54.5% in non-metro regions. This discrepancy highlights the importance of targeted efforts to ensure equitable vaccine access and uptake in both urban and rural areas. Strategies such as mobile vaccination clinics, community outreach programs, and targeted messaging tailored to specific regional needs can help bridge this gap and ensure comprehensive vaccine coverage across the country.


![piechart](https://github.com/deku1261/HealthCare_Project1/assets/124642442/48e168cd-c258-47b5-9b80-b28d62377af0)

Understanding the variation in COVID-19 vaccine administration across different states is crucial for assessing the progress and effectiveness of vaccination campaigns. To gain insights into this aspect, we analyzed the CDC data and created a bar graph showcasing the average COVID-19 vaccines administered in the top 10 states. This bar graph highlighted the variations in vaccine distribution among these states. The analysis revealed that certain states exhibited higher average vaccine administration rates compared to others. This disparity can be influenced by factors such as population size, vaccine allocation strategies, healthcare infrastructure, and public health initiatives. Identifying states with higher vaccination rates can serve as best practice examples for other regions, guiding policymakers and health authorities in implementing successful vaccination strategies. Moreover, this analysis underscores the need for targeted interventions and resource allocation to states with lower vaccination rates, ensuring an equitable distribution of vaccines and fostering nationwide immunization against COVID-19.

![barchart](https://github.com/deku1261/HealthCare_Project1/assets/124642442/26561cc0-b512-48d8-b8ff-2997c51ffea1)



