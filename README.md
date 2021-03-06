# Econometry-Oil
```diff
! Update
+ Due to the unavaibility of data the project shall be pivoted to be more mining focusd
+ for this a free AWS instance has been started that collected the daily data of RSP and logs to to a csv file.
+ A dashboard shall be created with the help of MERN to display the features of the collected data
+ Once enough data has been collected, the data shall be used to analyse the deeper market trend.
+ An alternative to RSP data, the BRENT index will be used for current predictions and analytics.
```
# Update - Phase 3 results
## Notable results
- Rural and urban Employment are negatively correlated. 
- Employment in urban areas is negatively correlated to retail selling price of oil.
<p align = "center" style="background-color:powderblue;">
<img src = "https://user-images.githubusercontent.com/67519229/123092836-8c35c500-d448-11eb-976d-d9db716205ef.jpg">
</p>

- Upon correlation and basic visualisation of collected data we found that macroeconomic factors are correlated to the selling price of oil as expected by the classical theoretical knowledge.

*Final Output is expected to be a dashboard*
```diff
+ Update June 4, 2021 16:45 IST
+ Basic Visualisations
+ Phase 3 Complete

- Next Update July 1, 2021
- Complete analytics
```
## What we aim to do with this project
- We have GDP data that is sector based.
- We have individual oil prices.
- We aim to find if there is a correlation between the taxes that the governements collects on the sold oil vs the Macroeconomic factors of the country itself.

- brentOILprices.csv has the oil prices indices that specify the cost per barrel internationally.
- GDP_INDIA.csv is the official RBI data that has the sectorwise GDP growth of the country per quater for the decade 2010-20
- Individual RSP data for the years 19,20,21 (Present) for major Metro cities.
- New.Csv is the processed data that has all the dates converted into a format that can be recognised by Pandas.
- Unemployment.csv is Unemployment Data from 2019 to 2020

## Phase 2 of project
- Collection of more data.
- Cleaning of the said data.

## Phase 3
- Processing the data into meaningful outputs and visualisations

## Phase 4 {Bypassed - Reason cited - lack of data}
- Using Econometric tests and confirming if there is a correlation present

## Phase 5
- Collection of inflation data
- Creation of Dashboard.

## To Run
### Windows
```diff
python -m venv newvenv
./newnev/Scripts/activate
```

### MacOS/Linux
```diff
python -m venv newenv
source ./newenv/bin/activate
```

```diff
+ Latest Commit: [June 4]
+ Completion of Phase 3

! Current work:
! ML Models and Visualisations

- Next Commit:
- Basic MERN architecture of dashboard


! Direction Forward:
! Visualise the said data.
! Create seperate files for getting visualisations.
! Use any cloud service for realtime data viewing and editing
```

## Notebook not Visible

- Getting the message "Sorry, something went wrong. Reload?" when viewing an *.ipynb on a GitHub blob page.
```diff
+ Probably a problem with the GitHub notebook viewing tool - sometimes github fails to render the ipynb notebooks, 
+ I believe that is some temporary (and recurring) issue with their backend

- A workaround

+ Try to open that notebook that you want using nbviewer online, you don't need to install it.
```
### Open "https://nbviewer.jupyter.org/"
### Paste the links 
- [Data-organising.ipynb](https://github.com/shuklasaharsh/Oil-Price-Analysis-Data/blob/main/Data-organising.ipynb)
- [Visualisation-and-analytics.ipynb](https://github.com/shuklasaharsh/Oil-Price-Analysis-Data/blob/main/Visualisation%20and%20analytics.ipynb)

```diff
+ The Notebook should be visible.
```

