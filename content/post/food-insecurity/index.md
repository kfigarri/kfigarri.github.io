---
title: 🍚 Food Insecurity Early Warning System
summary: 🏆 Winner of the Best Visualization Award — UN Big Data Hackathon 2022 (Youth Track)
date: 2022-11-11
authors:
  - admin
tags:
  - UN Datathon
  - Machine Learning
  - Data Science
featured: false
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bundle-of-assorted-vegetable-lot-xMh_ww8HN_Q)'
  focal_point: ''
  preview_only: false
---

## Overview

At the 2022 United Nations Big Data Hackathon, Team 4SKA1—formed by young Indonesian data scientists including myself—took on the global challenge of **Food Insecurity**. Our solution was a scalable **Early Warning System** prototype built using open data and visualized via Google Data Studio. The project won **[Best Visualization Award](https://unstats.un.org/bigdata/events/2022/hackathon/winners-y.cshtml)** in the Youth Track for its clarity, insight, and practical utility.

## The Challenge

Climate change and socio-economic instability are increasingly affecting global food security. Yet, early warning systems are often absent, especially in vulnerable regions. Our task was to answer:

- _Can we monitor and anticipate food insecurity trends globally?_  
- _How does a country’s food insecurity affect others through trade flows?_  

## Our Approach

We created a predictive model using data from:
- The UN Hackathon 2022 datasets  
- World Bank, AtlasBig, and OurWorldInData

We engineered three key scores for each country:
- **Socio-Economic Score (SES)**: clustering countries based on unemployment, undernourishment, mortality, etc.
- **Climate Score**: using PCA to combine metrics like CO₂ emissions, energy use, forest area.
- **Food Score**: integrating food production, consumption, waste, and trade patterns.

These were combined to train a **linear regression model** to estimate national food insecurity scores with ~10% error.

## The Dashboard Prototype

We built an interactive **Google Data Studio dashboard** to visualize:
- Global food insecurity status by country
- SES, Climate, and Food score comparisons
- Country-level food trade relationships
- Exploratory visualizations to empower policy and humanitarian decisions

👉 [View the Dashboard](https://datastudio.google.com/reporting/41fbab8b-e176-483e-b6df-e61161e57b97)

📄 [Download Full Project PDF](https://drive.google.com/file/d/13YdcGpIG4kUS8YbUFLS2T4ciPQEivylf/view?usp=sharing)


### Did you find this page helpful? Consider sharing it 🙌