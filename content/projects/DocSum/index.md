---
title: "DocSum"
date: 2020-02-02T17:18:12-05:00
featured: true
description: "A tool to automatically summarize documents using the BART Machine Learning Model."
tags: ["Machine Learning"]
resources:
- name: "image"
  src: "docsum.jpg"
link: "https://github.com/HHousen/DocSum"
weight: 500
sitemap:
  priority : 0.8
---

A tool to automatically summarize documents using the BART Machine Learning Model.

BART ([BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation, Translation, and Comprehension](https://arxiv.org/pdf/1910.13461.pdf)) is the state-of-the-art in text summarization as of 02/02/2020. It is a "sequence-to-sequence model trained with denoising as pretraining objective" ([Documentation & Examples](https://github.com/pytorch/fairseq/blob/master/examples/bart/README.md)).

This tool will convert a PDF to XML and then interpret that XML file using the `font` property of each `text` element.
