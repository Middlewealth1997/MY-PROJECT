# MY-PROJECT

# Covid-19 

## Problem Statement

This dashboard helps the World Health Organisation (WHO) understand the high transmission rate of Covid-19 Pandemic across the country. It helps the WHO know the flow of the Pandemic across the country. This dashboard shows the number of confirmed cases in each country and region and their recovered cases of Covid-19 Pandemic.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present.
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 7 : Four card visuals were added to the canvas, one representing Sum of New Cases, Sum of Deaths, Sum of Recovered and sum of confirmed cases.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.

- Step 8 : A column chart was also added to the report design area representing the sum of recovered by WHO region. A bar chart was also added to the report design to represent Sum of Deaths by country/region, also a Map showing the Country/region by sum of deaths, and lastly a pie chart representing number of new cases by their country/region. 
- Step 9 : Ratings Visual was used to represent different ratings mentioned below,

  (a) Active

  (b) Confirmed

  (c) Country/Region

  (d) Date

  (e) Deaths

  (f) New Cases

  (g) New Deaths

  (h) New Recovered

  (i) Recovered

  (j) WHO Region

In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some cases.

- Step 10 : In the report view, under the insert tab, one text box were added to the canvas, the name of the report was mentioned.
- Step 11 : In the report view, under the insert tab, using image option from elements group a image was inserted company's logo was added to the report design area. 
        
- Step 12 : A card visual was used to calculate the sum of Deaths.

<img width="115" alt="sum of deaths" src="https://github.com/user-attachments/assets/7036743c-ffda-4059-b1dc-ec2227c44dd0">

        
 - Step 13 : A card visual was used to calculate the sum of new cases.

img width="116" alt="new cases" src="https://github.com/user-attachments/assets/c0a927d9-f973-49ad-8b2e-20354e97826d">


 - Step 14 : A card visual was used to calculate the sum of Recovered.

<img width="109" alt="sum of recovered" src="https://github.com/user-attachments/assets/2085fdd7-2c75-4534-9866-5f2285208257">

 - Step 15 : A card visual was used to calculate the sum of confirmed cases.

<img width="107" alt="sum of confirmed " src="https://github.com/user-attachments/assets/e56f0e29-75f9-48bf-bb91-90cbd809d859">

 - Step 16 : The report was then published to Power BI Service.

<img width="536" alt="dashboard report covid" src="https://github.com/user-attachments/assets/dc7872ed-4263-4aa3-8d44-ce71d6e4bde9">
