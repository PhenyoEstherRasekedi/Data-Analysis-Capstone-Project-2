# Dano Airlines

## Data driven strategy to increase satisfaction rate at Dano Airlines

### Project Overview

This data analysis project aims to provide insights into the latest passenger survey results of Dano Airlines that shows satisfaction rate dipped under 50% for the first time ever. By analysing various aspects of the survey results, I seek to analyze the data to find the key areas for the leadership team to focus on and data driven recommendations to get back on track.

### Data Sources

Survey Results: The primary dataset used for this analysis is the 'airline_data.xlsx' file, containing detailed information about each passenger, their flight, and type of travel, as well as their evaluation of different factors like cleanliness, comfort, service, and overall experience.

### Tools

- Microsoft Excel- Data Cleaning, Data Analysis, Creating Report
  - [Download here](https://microsoft.com)

### Data Cleaning/Preparation

In the initial data preparation phase, I performed the following tasks:

1. Data loading and inspection.
2. Data Formating

### Exploratory Data Analysis

EDA involved exploring the survey results to answer key questions, such as:

- Which areas are passengers most unsatisfied with?
- Does the passenger demographic indicate certain age groups or gender are more unsatisfied than the other?
- Which key areas need improvement for each ticket class?
- Does reason for travelling influence satisfaction? does it indicate a bias in the results.
- Which key areas were first time travellers most unsatisfied with?

### Data Analysis

An interesting formula I worked with was an if statement to categorize the age into age brackets and flight distance into duration type.

`=IF(C129741>55,"Old",IF(C129741>=31,"Middle Age",IF(C129741<31,"Adolescent","Invalid")))`

`=IF(H2>4000,"Long",IF(H2>=1001,"Medium",IF(H2<=1000,"Short","invalid")))`

### Results/Findings

The analysis results are summarized as follows:

1. Passengers are unsatisfied or neutral about 8 of 16 areas evaluated in the survey. These are baggage handling, food and drinks, in-flight service, check-in service, arrival delay, departure delay, ease of online booking and lastly departure and arrival time convinience.
2. Middle age passengers are more satisfied across most areas in comparison to old and adolescents passengers. Male and Females are mostly similar in that they are neutral or unsatisfied in all areas except when they are travelling for business.
3. For Economy and Economy Plus, most are neutral or unsatisfied with the arrival and departure delay. For Business class, the passengers are satisfied with all areas however, improvement could be made in flight delays as well.
4. Most passengers travelling for business purposes where satisfied with all areas except arrival delay. Whilst most passengers travelling for personal reasons where unsatisfied or neutral on all areas. It could be argued that business passengers are usually in a hurry and focused on their destinations so pay no mind to small details. While those travelling for personal reasons like vacations are more mindful of the whole flight experience.
5. A majority of first time customers were travelling for business purposes and were unsatisfied with the arrival delay.
