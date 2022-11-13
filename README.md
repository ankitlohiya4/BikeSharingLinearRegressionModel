# Project Name
> This case study is to understand 
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands.
- To create a linear model that quantitatively relates the demand for shared bikes with the available independent variables.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

Essentially, the company wants —
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands.
- To create a linear model that quantitatively relates the demand for shared bikes with the available independent variables.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The equation of our best fitted line is:
- cnt = 0.2331 * yr  +  0.0515 * workingday  +  0.6022 * temp  -  0.1388 * windspeed  +  0.1052 * Winter + 0.0617 * Sat  -  0.2546 * Light Rain  +  0.0531

The variables that are significant in predicting the demand for shared bikes are
- temp
- yr
- Winter

The demand of the bike increases by
- 0.6022 times with increase in 1 uint of tempereature provided all other variables remain constant
- 0.2331 times with increase in 1 year provided all other variables remain constant

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.21.5
- pandas - version 1.4.2
- matplotlib - version 3.5.1
- seaborn - version 0.11.2
- statsmodels - version 0.13.5
- sklearn - version 1.1.3

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project is done as part of Execution PG on ML & AI from upgrade with partnership with IIITB


## Contact
Created by [@ankitlohiya4] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->