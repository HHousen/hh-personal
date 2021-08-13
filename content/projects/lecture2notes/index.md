---
title: "lecture2notes"
date: 2019-11-17T11:39:16-05:00
featured: true
description: "For this project, I was named a top 300 Regeneron STS scholar. Lecture2notes is a state-of-the-art system to summarize classroom lectures using machine learning."
tags: ["Machine Learning"]
resources:
- name: "image"
  src: "research.png"
link: "https://github.com/HHousen/lecture2notes/"
weight: 500
sitemap:
  priority : 0.8
---

**For this research project, I was named a [top 300 scholar](https://www.societyforscience.org/regeneron-sts/2021-scholars/) in the [Regeneron Science Talent Search](https://www.societyforscience.org/regeneron-sts/) 2021, the nation’s oldest and most prestigious science and math competition for high school seniors.**

[![GitHub license](https://img.shields.io/github/license/HHousen/lecture2notes.svg)](https://github.com/HHousen/lecture2notes/blob/master/LICENSE) [![Github commits](https://img.shields.io/github/last-commit/HHousen/lecture2notes.svg)](https://github.com/HHousen/lecture2notes/commits/master) [![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) [![Documentation Status](https://readthedocs.org/projects/lecture2notes/badge/?version=latest)](https://lecture2notes.readthedocs.io/en/latest/?badge=latest) [![GitHub issues](https://img.shields.io/github/issues/HHousen/lecture2notes.svg)](https://GitHub.com/HHousen/lecture2notes/issues/) [![GitHub pull-requests](https://img.shields.io/github/issues-pr/HHousen/lecture2notes.svg)](https://GitHub.com/HHousen/lecture2notes/pull/) [![DeepSource](https://static.deepsource.io/deepsource-badge-light-mini.svg)](https://deepsource.io/gh/HHousen/lecture2notes/?ref=repository-badge)

**[Research Paper](/media/lecture2notes-paper-v1.pdf)** / **[Documentation](https://lecture2notes.readthedocs.io/en/latest)** / **[GitHub](https://github.com/HHousen/lecture2notes/)**

**Lecture2Notes** is a project that **summarizes lectures videos**. At a high level, it parses both the **visual** and **auditory** components of the video, **extracts text** from each, **combines** them, and then **summarizes** the combined text using **automatic** summarization algorithms.

**Check out [the documentation](https://lecture2notes.readthedocs.io/en/latest) for usage details.**

**To get started summarizing text**, visit [the tutorial](https://lecture2notes.readthedocs.io/en/latest/getting-started/tutorial.html).

**Abstract:** Note-taking is a universal activity among students because of its benefits to the learning process. This research focuses on end-to-end generation of formatted summaries of lecture videos. Our automated multimodal approach will decrease the time required to create notes, increase quiz scores and content knowledge, and enable faster learning through enhanced previewing. The project is broken into three main components: the slide classifier, summarization models, and end-to-end-process. The system beings by extracting important keyframes using the slide classifier, a deep CNN. Then, unique slides are determined using a combination of clustering and keypoint matching. The structure of these unique slides is analyzed and converted to a formatted transcript that includes figures present on the slides. The audio is transcribed using one of several methods. We approach the process of combining and summarizing these transcripts in several ways including as keyword-based sentence extraction and temporal audio-slide-transcript association problems. For the summarization stage, we created TransformerSum, a summarization training and inference library that advances the state-of-the-art in long and resource-limited summarization, but other state-of-the-art models, such as BART or PEGASUS, can be used as well. Extractive and abstractive approaches are used in conjunction to summarize the long-form content extracted from the lectures. While the end-to-end process and each individual component yield promising results, key areas of weakness include the speech-to-text algorithm failing to identify certain words and some summarization methods producing sub-par summaries. These areas provide opportunities for further research.
