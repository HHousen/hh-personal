---
title: "Unsupervised Object Discovery"
date: 2023-04-13T00:16:03-04:00
featured: true
description: "An implementation of several state-of-the-art machine learning models that discover objects in images without being told what an object is."
tags: ["Machine Learning"]
resources:
- name: "image"
  src: "find_object_logo.png"
- name: "example"
  src: "sa_clevr6_example.png"
link: "https://github.com/HHousen/object-discovery-pytorch"
weight: 103
sitemap:
  priority : 0.8
---

[![GitHub license](https://img.shields.io/github/license/HHousen/object-discovery-pytorch.svg)](https://github.com/HHousen/object-discovery-pytorch/blob/master/LICENSE) [![Github commits](https://img.shields.io/github/last-commit/HHousen/object-discovery-pytorch.svg)](https://github.com/HHousen/object-discovery-pytorch/commits/master) [![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) [![GitHub issues](https://img.shields.io/github/issues/HHousen/object-discovery-pytorch.svg)](https://GitHub.com/HHousen/object-discovery-pytorch/issues/) [![GitHub pull-requests](https://img.shields.io/github/issues-pr/HHousen/object-discovery-pytorch.svg)](https://GitHub.com/HHousen/object-discovery-pytorch/pull/)

> This is an implementation of several unsupervised object discovery models (Slot Attention, SLATE, GNM) in PyTorch with pre-trained models.

{{< imgproject image="example" caption="An example of the results of the Slot Attention model on the CLEVR dataset." >}}

Unsupervised object discovery is the task of segmenting objects in an image without ever being given a label indicating where the objects are. You can view more visualization like the one on this page in the [visualizations section of the README](https://github.com/HHousen/object-discovery-pytorch#more-visualizations).
