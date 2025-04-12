---
title: "AI Respiratory Doctor"
date: 2019-07-08T13:35:48-04:00
featured: true
description: "A flask web app template for use with machine learning projects. Currently contains complete example code to run a fully functional X-Ray diagnosis AI."
tags: ["Machine Learning", "Web Development"]
resources:
- name: "image"
  src: "doctor.png"
weight: 500
sitemap:
  priority : 0.8
---

#### Website

Over 93% Accuracy &#8226; Advanced Powerful AI &#8226; Easy & Simple to Use

This project is a functional full-stack web app that includes features such as login and signup functionality with a database through Flask-Login, beautiful design thanks to [Materialize.css](https://materializecss.com/), an easy to understand backend because of [Flask](http://flask.pocoo.org/), best practices for production servers, and a state-of-the-art X-Ray Classifier powered by [fast.ai](https://docs.fast.ai/). The AI was trained on  over 100,000 anonymized chest x-ray images from more than 30,000 patients ([NIH Dataset](https://www.nih.gov/news-events/news-releases/nih-clinical-center-provides-one-largest-publicly-available-chest-x-ray-datasets-scientific-community)).

Website GitHub repo: <https://github.com/HHousen/ai-respiratory-doctor>

#### Electron App

I also created an [electron](https://electronjs.org/) app for this project. It uses a self-contained python [flask](https://flask.palletsprojects.com/en/1.1.x/) API, and [pytorch](https://pytorch.org/)/[fastai](https://docs.fast.ai/) to compute the probabilities of certain diseases in chest X-Rays using machine learning.

Asset bundling is handled by webpack through [electron-webpack](https://github.com/electron-userland/electron-webpack) and building/compiling is done with [electron-builder](https://github.com/electron-userland/electron-builder). The user interface was built using the Materialize-css framework. The original template this app was based on is [electron-webpack-quick-start](https://github.com/electron-userland/electron-webpack-quick-start).

Additionally, [Travis CI](https://travis-ci.org/) handles automatic building of the application on every commit.

Electron GitHub repo: <https://github.com/HHousen/ai-respiratory-doctor-electron>
