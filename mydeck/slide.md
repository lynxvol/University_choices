University Choices
========================================================
author: Sarah Amalyna, Wei Seong Lee, Min Hua Lee
date: 
autosize: true


<style type='text/css'>
img {
    max-height: 504px;
    max-width: 867px;
}

p {
    font-size: 28px;
}
</style>

Project Objective
========================================================

Nowadays, there are so many university choices that making decision is hard especially at a very young age. We wanted to help by creating a shiny app that can help prospect student to make a right decision that will determine their next 5 years of student life.

Goal:

>1. To create shiny app that can help student to find out which university or college suit them the most based on their preferral( location, school type, salary range ).

>2. To create a shiny app that can show a plot of salary increase accross time so that student know what salary range to expect after graduating.  



Project Flow
========================================================

>1. Getting the data :  
  The datasets come from Kaagle "Where it pays to attend college".  
  Link: https://www.kaggle.com/wsj/college-salaries.  
  There are 3 datasets all together.
 
>2. Clean the data:  
  > a. Some of the value are converted to the right format.  
  > b. Arranged columns and merged overlapping file together.  
  > c. Replace all missing values with relevant values.  

>3. Create Shiny  
> a. Create ui (slider input, checkbox input, tab, etc.)  
> b. Creates server (leaflet, plot,chart,visualization)

Data Set Description
========================================================

The dataset was originally obtained from the Wall Street Journal based on data from Payscale, Inc.
Contains 3 files:  

> 1. Salaries-by-college-type.csv: 
Contains information on School Name, School Type, Salary Information. 

> 2. Salaries-by-Region.csv: 
Contains the School Name, region and Salary Information. 

> 3. Degrees-that-Pay-Back.csv:  
Contains information such as Major and Salary Information. 

Shiny Application
========================================================
![App](./Map.png)

Link to Shiny Application: https://lynxvol.shinyapps.io/University_Choices/  
Link to GitHub: https://github.com/lynxvol/University_choices  
