# Project Name
> This is a linear regression project where we are analysing the data for US bike-sharing provider BoomBikes to understand the dips in their revenues. We are trying establish relationship between different variables and final sales.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

> In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

> The company wants to know:
1) Which variables are significant in predicting the demand for shared bikes.
2) How well those variables describe the bike demands

> We will be using days.csv data for analysis 

## Conclusions
### Summary

For our final prediction we will rely on the manual model as we are getting the desired result

##### Equation: 

cnt = 0.113 + 0.481×temp + 0.113×winter + 0.094×summer - 0.084×mistCloudy - 0.296×lightSnow + 0.067×sat + 0.115×sep + 0.042×oct - 0.047×jan + 0.053×aug - 0.163×windspeed + 0.056×workingday + 0.234×yr

#### Important values:
1. Train dataset R^2 : 0.843
   
2. Test dataset R^2 : 0.791
   
3. Train dataset Adjusted R^2 : 0.839
   
4. Test dataset Adjusted R^2 : 0.777
   
#### Significant variables:
1.year

2.workingday

3.temperature

4.windspeed

5.Season(Winter, Summer)

6.months(August, October, September,January)

7.weathersit( Light Snow, Mist Cloudy)

8.Days(Saturday)

#### Inferences¶
Company should focus on Winter and Summer Season to expand the business as the demand is high

Demand for bikes is less in Mist Cloudy and Light snow weather situations. So not a right time for business

On Saturdays the demand for shared bike is high

Months Aug, Sep , Oct are good for shared bike business whereas in January the business is showing downward trend

If WindSpeed is high demand for bike is less

On Workingdays demand for bike is high

Year 2019 has seen a higher demand for shared bikes compared to 2018.¶


## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
