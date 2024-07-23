# Covid-19-Report

## Problem Statement

This dashboard helps the World Health Organisation (WHO) understand the cases of Covid-19. It helps them know the number of cases confirmed in each country/region, they get to know their number of cases, number of death and those recovered from the Covid-19. it also let them know the number of cases by each country, with this dashboard they have identified the cases and further work on their process.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : In the report view, under the view tab, theme was selected.
- Step 5 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 6 : Four card visuals were added to the canvas, one representing Total deaths, total positive cases, total new cases & Total recovering case.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
- Step 7 : A bar chart was also added to the report design area representing the Death by Country/Region. 
- Step 8 : Ratings Visual was used to represent different ratings mentioned below,

  (a) Active

  (b) Confirmed

  (c) Country/Region

  (d) Date

  (e) Deaths

  (f) New Cases

  (g) New Death

  (h) New Recovered

  (i) Recovered

  (j) WHO Region

  
In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some cases.

All these values have been ignored while calculating rating for each of the parameters mentioned above.

- Step 9 : In the report view, under the insert tab, one text boxes were added to the canvas, the name of the report was mentioned.
- Step 10 : In the report view, under the insert tab, using image option from elements group a rectangle was inserted & similarly using image option company's logo was added to the report design area. 
- Step 11 : A card visual was used to represent sum of deaths.

![total death](https://github.com/user-attachments/assets/25eea56e-eb7b-4c4f-80c2-fcc3e7ddd89c)

        
 - Step 12 : A card visual was used to represent the Total Positive Cases.

![positive cases](https://github.com/user-attachments/assets/f3cf638d-9655-4a4b-ad44-fbfa7f6c9096)


 - Step 13 : A card visual was used to represent the Total number of New Cases.

![new cases](https://github.com/user-attachments/assets/3f49278a-f4a2-4992-b224-e7dadce0849f)

Step 14 : A card visual was used to represent the Total number of Recovery Cases.

![recovered caes](https://github.com/user-attachments/assets/611c2894-49bd-436f-9d37-eea7f9b4bdfa)

 - Step 15 : The report was then published to Power BI Service.


![dashboard](https://github.com/user-attachments/assets/6d420fbe-3421-424f-9bcd-c9365ad552e2)
