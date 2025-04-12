---
title: "Will I Have a Snow Day"
date: 2020-09-24T17:39:41-04:00
featured: true
description: "130,000+ users in winter 2024. Simply enter your zip code and an advanced AI will calculate your chance of having a snow day for the next few days."
tags: ["Machine Learning", "Web Development"]
resources:
- name: "image"
  src: "wihasd-logo.png"
- name: "social"
  src: "wihasd-social.png"
link: "https://willihaveasnowday.com"
weight: 102
sitemap:
  priority : 0.8
---

Will I Have A Snow Day.com (WIHASD) is a website that will **calculate your chance of having a snow day** using an **AI model**. The model has learned what weather conditions cause snow days by inspecting **decades of data**, more than any human could analyze.

{{< imgproject image="social" resize="600x600" >}}

The site experienced **tremendous growth** during winter 2024, serving over **130,000 users** who relied on its predictions to anticipate potential snow days in their areas.

Importantly, WIHASD has a mechanism that enables it to **improve its accuracy over time**. When you make a prediction you can sign up to receive an email the day of the predicted snow day. The email will ask **if the model's prediction was correct**. The captured weather data and your label (whether or not you had a snow day) will be added to the database used to train the model, thus giving it more information about the **weather conditions** and your specific **zip code**.

Powered by XGBoost, scikit-learn, Materialize.css, SendGrid, and Flask. Scraped school closings and processed **100GB+** of weather data from NOAA to build a snow day dataset. Trained a gradient boosting classifier after extensive data exploration and feature engineering.

The site no longer works because the model has not been updated since 2020. Nevertheless, I learned a lot about classical machine learning, handling large datasets, web scraping, building full-stack websites with Flask, and even a little distributed training with Dask.

GitHub Repository: <https://github.com/HHousen/willihaveasnowday>
