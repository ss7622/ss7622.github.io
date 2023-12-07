---
layout: page
title: About Project
permalink: /about/
---

# BlueSkySeoul

Fine dust cleaning project for Seoul

Main aim: First, using data related to city buses, we identify areas with high pedestrian traffic to determine locations for the installation of outdoor fine dust reduction devices. Second, based on areas with high pedestrian traffic, we establish routes for street cleaning vehicles to ensure that fine dust reduction is noticeable to the citizens.

Emphasizing the open-source nature of our project, we believe that the positive outcomes extend not only to economic benefits but also address citizens' discomfort, enhance public health, and improve overall convenience for citizens.

documetation link: https://blueskyseoul.readthedocs.io/en/latest/

Korean version: https://github.com/coldbeeen/BlueSkySeoul/blob/main/README_ko.md


## Project Naming and Branding

We named our project BlueSKySeoul, in hopes of cleaner air in Seoul.
"BlueSkySeoul" is our brand name as well. It encompasses the essence of our project, making it an ideal choice for both our project name and brand.



## Problem Identification & Analysis

Due to the end of COVID-19 pandemic, people almost wear off their masks and they are exposed to the danger of fine dust again. Fine dust is very harmful to the bronchi, so we need to find ways to reduce fine dust.

Usually, we can see that the level of fine dust is highly increasing in Spring and Winter. As winter comes to an end, the West wind blows on Korea as you can see in Picture 1. Then a lot of fine dust from China also comes into Korea, which makes the city as you can see in Picture 2. This phenomenon results in air quality deterioration, and so negatively impacts the healthiness of the citizens.



## Our Actions & The Impact

### Our Actions
1. Air Pollution Analysis
- We will analyze the average daily air pollution level in Seoul and calculate the average air pollution level by autonomous district by month, and will select as the target area for installation of ‘street-lamp type fine dust reducer.

2. Analyzing bus data
- We will analyze the number of people getting on and off at each bus stop in Seoul because we thought that the large floating population will cause a high concentration of fine dust.

3. Potential Challenges
- Refining outdoor fine dust reduction devices installation criteria
Collect road traffic counts in addition to bus boarding and alighting counts for more efficient installation locations.

-Refining road cleaning vehicle routes
Collecting foot traffic data allows for better optimization of street sweeper routes

-Real-time data updates
Through API data, we can utilize real-time changing air quality and population information to flexibly modify the routes of our vehicles.

Through the above process, we will do:
i. Installation of outdoor fine dust reduction devices at the top 10 stops for the number of people getting on and off.
ii. Road cleaning vehicle routes by clustering the top 100 stops for getting on and off.

### The Impact
Benefit from our project: If the findings of this report are incorporated into policy, it is expected that the improvement of citizen's policy satisfaction rate will be evident, as the persistent issue of reducing fine dust is something that citizens can directly feel. In fact, according to a recent interview survey [1], there have been cases where the installation of fine dust reduction devices in outdoor spaces has led to a sense of relief. 

Furthermore, according to the Busan Institute of Health and Environment [2], the economic impact of policies aimed at reducing fine dust, including a potential decrease in the number of fatalities, is estimated to be as high as 582.5 billion KRW. 

Therefore, based on the analysis results, positive outcomes can be anticipated not only in terms of economic benefits from fine dust reduction but also in terms of addressing citizens' discomfort, enhancing public health, and improving convenience for citizens.

[1] https://www.etnews.com/20200602000213

[2] http://www.bosa.co.kr/news/articleView.html?idxno=2195298



## Code Explanation

### Preferred Development Languages
We'll be using Python, which has powerful libraries and a rich ecosystem that makes it easy to collect, analyze, and visualize data.

IPYNB stands for "Interactive Python Notebook." It is a file format and associated software application used for interactive computing. IPYNB files are often referred to as Jupyter Notebooks, named after the Jupyter open-source project that supports them.

A Jupyter Notebook is an open-source web application that allows you to create and share documents containing live code, equations, visualizations, and narrative text. It supports various programming languages, but it is most commonly used with Python.


### Python libraries to use in this project

- Pandas
- Matplotlib.pyplot
- Folium
- Requests
- Json
- Sklearn.cluster
- DBSCAN


## Team Member's Info

- Taeho Kim: Team Leader, Data Visualization
- Chanbeen Lee: Data Preprocessing, Modeling
- Seulbeen Je: EDA, Data Preprocessing
- Junbeom Lee: Data Visualization, Data Crawling
