---
title: "AI Respiratory Doctor Desktop App"
date: 2019-09-01T16:49:26-04:00
featured: true
description: "A desktop app built with Electron that mimics the AI Respiratory Doctor web app."
tags: ["Machine Learning", "Web Development", "App Development"]
resources:
- name: "image"
  src: "doctor.png"
link: "https://github.com/HHousen/ai-respiratory-doctor-electron"
weight: 500
sitemap:
  priority : 0.8
---

This app uses [electron](https://electronjs.org/), a self-contained python [flask](https://flask.palletsprojects.com/en/1.1.x/) API, and [pytorch](https://pytorch.org/)/[fasiai](https://docs.fast.ai/) to compute the probabilities of certain diseases in chest X-Rays using machine learning.

Asset bundling is handled by webpack through [electron-webpack](https://github.com/electron-userland/electron-webpack) and building/compiling is done with [electron-builder](https://github.com/electron-userland/electron-builder). The user interfact was built using the Materialize-css framework. The original template this app was based on is [electron-webpack-quick-start](https://github.com/electron-userland/electron-webpack-quick-start).

Additionally, [Travis CI](https://travis-ci.org/) handles automatic building of the application on every commit.

Original App: [Project Page](/projects/ai-respiratory-doctor/)