---
title: "TransformerSum"
date: 2020-07-16T23:01:35-04:00
featured: true
description: "Models to perform neural summarization (extractive and abstractive) using machine learning transformers."
tags: ["Machine Learning"]
resources:
- name: "image"
  src: "transformersum.jpg"
link: "https://github.com/HHousen/TransformerSum"
weight: 500
sitemap:
  priority : 0.8
---

[![GitHub license](https://img.shields.io/github/license/HHousen/TransformerSum.svg)](https://github.com/HHousen/TransformerSum/blob/master/LICENSE) [![Github commits](https://img.shields.io/github/last-commit/HHousen/TransformerSum.svg)](https://github.com/HHousen/TransformerSum/commits/master) [![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) [![Documentation Status](https://readthedocs.org/projects/transformersum/badge/?version=latest)](https://transformersum.readthedocs.io/en/latest/?badge=latest) [![GitHub issues](https://img.shields.io/github/issues/HHousen/TransformerSum.svg)](https://GitHub.com/HHousen/TransformerSum/issues/) [![GitHub pull-requests](https://img.shields.io/github/issues-pr/HHousen/TransformerSum.svg)](https://GitHub.com/HHousen/TransformerSum/pull/) [![DeepSource](https://static.deepsource.io/deepsource-badge-light-mini.svg)](https://deepsource.io/gh/HHousen/TransformerSum/?ref=repository-badge)

`TransformerSum` is a library that aims to make it easy to *train*, *evaluate*, and *use* machine learning **transformer models** that perform **automatic summarization**.

It features tight integration with [huggingface/transformers](https://github.com/huggingface/transformers) which enables the easy usage of a **wide variety of architectures** and **pre-trained models**.

There is a heavy emphasis on code **readability** and **interpretability** so that both beginners and experts can build new components. Both the extractive and abstractive model classes are written using [pytorch_lightning](https://github.com/PyTorchLightning/pytorch-lightning), which handles the PyTorch training loop logic, enabling **easy usage of advanced features** such as 16-bit precision, multi-GPU training, and [much more](https://pytorch-lightning.readthedocs.io/).

`TransformerSum` supports both the extractive and abstractive summarization of **long sequences** (4,096 to 16,000 tokens) using the [longformer](https://huggingface.co/transformers/model_doc/longformer.html) (extractive) and [LongformerEncoderDecoder](https://github.com/allenai/longformer/tree/encoderdecoder) (abstractive), which is a combination of [BART](https://huggingface.co/transformers/model_doc/bart.html) ([paper](https://arxiv.org/abs/1910.13461)) and the longformer. `TransformerSum` also contains models that can run on resource-limited devices while still maintaining high levels of accuracy.

Models are automatically evaluated with the **ROUGE metric** but human tests can be conducted by the user.

**Check out [the documentation](https://transformersum.readthedocs.io/en/latest) for usage details.**
