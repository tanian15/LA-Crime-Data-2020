# LA Crime Data from 2020 Exploration

## Project Overview
- Data exploration using a dataset from the [LAPD](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8/about_data) to answer questions regarding the crime cases.
- Used Matplotlib and Seaborn to create visualizations in Python.
- Visualization of the crimes documented with a victim age of zero in Tableau.

## Objectives
##### Create visualizations to answer these questions:
- Which area in LA has the most crime?
- Why is the victim age "0" so high?
- Which weapons are used the most?
- What is the ethnicity distribution of victims?

## Visualizations
- [Tableau dashboard](https://public.tableau.com/app/profile/tania.nixon/viz/LACRIME_17394229663650/Age0Crime?publish=yes)

## Conclusions
- Bodily force is the most common "weapon"
- The victim age being zero is extremely high. Looking further, the LAPD reports the victim age as zero if no person was directly affected (stolen vehicle, theft, etc). There were also some negative ages listed (-4, -3, -2, -1) which I changed to age 0. Therefore, the most common victim age is thirty.
- The majority of victims are Latino, followed by White and Black.
- Surprisingly the victim gender distribution is almost even with males being slightly higher than females.
