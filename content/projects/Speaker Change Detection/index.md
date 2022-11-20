---
title: "Speaker Change Detection"
date: 2022-11-19T19:17:10-05:00
featured: true
description: "An implementation of a machine learning architecture that detects when the current speaker changes in an audio file."
tags: ["Machine Learning"]
resources:
- name: "image"
  src: "sound.png"
- name: "segmentation"
  src: "segmentation.gif"
link: "https://github.com/HHousen/speaker-change-detection"
weight: 108
sitemap:
  priority : 0.8
---

[![GitHub license](https://img.shields.io/github/license/HHousen/speaker-change-detection.svg)](https://github.com/HHousen/speaker-change-detection/blob/master/LICENSE) [![Github commits](https://img.shields.io/github/last-commit/HHousen/speaker-change-detection.svg)](https://github.com/HHousen/speaker-change-detection/commits/master) [![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) [![GitHub issues](https://img.shields.io/github/issues/HHousen/speaker-change-detection.svg)](https://GitHub.com/HHousen/speaker-change-detection/issues/) [![GitHub pull-requests](https://img.shields.io/github/issues-pr/HHousen/speaker-change-detection.svg)](https://GitHub.com/HHousen/speaker-change-detection/pull/)

> Implementation of ["End-to-end speaker segmentation for overlap-aware resegmentation"](https://arxiv.org/abs/2104.04045) with modifications for speaker change detection. Learn more in the [presentation](https://github.com/HHousen/speaker-change-detection/blob/master/media/Speaker%20Change%20Detection%20Presentation.pdf).

{{< imgproject image="segmentation" caption="GIF showing segmentation training progress (more details in the [presentation](https://github.com/HHousen/speaker-change-detection/blob/master/media/Speaker%20Change%20Detection%20Presentation.pdf))" >}}

This project is a machine learning architecture that takes in an audio file and outputs the timestamps where the active speaker changes. However, it can also identify when people are speaking and even distinguish speakers if they are talking simultaneously. It contains functions to prepare data, train, and perform inference for these two tasks, which are formally known as speaker change detection and speaker segmentation.
