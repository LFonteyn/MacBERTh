---
abstract: >-
  The new pre-train-then-fine-tune paradigm in Natural Language Processing (NLP)
  has made important performance gains accessible to a wider audience. Once
  pre-trained, deploying a large language model presents comparatively small
  infrastructure requirements, and offers robust performance in many NLP tasks.
  The Digital Humanities (DH) community has been an early adapter of this
  paradigm. Yet, a large part of this community is concerned with the
  application of NLP algorithms to historical texts, for which large models
  pre-trained on contemporary text may not provide optimal results. In the
  present paper, we present "MacBERTh"---a transformer-based language model
  pre-trained on historical English---and exhaustively assess its benefits on a
  large set of relevant downstream tasks. Our experiments highlight that,
  despite some differences across target time periods, pre-training on
  historical language from scratch outperforms models pre-trained on present-day
  language and later adapted to historical language.

  [Note: The updated and extended version of this paper is: "Adapting vs Pre-training Language Models for Historical Languages"]
url_pdf: ""
title: "MacBERTh: Development and Evaluation of a  Historically Pre-trained
  Language Model for English (1450-1950)"
publication_types:
  - "1"
authors:
  - Enrique Manjavacas
  - Lauren Fonteyn
summary: This paper presents "MacBERTh", a transformer-based language model
  pre-trained on historical English, and exhaustively assess its benefits on a
  large set of relevant downstream tasks. Our experiments highlight that,
  despite some differences across target time periods, pre-training on
  historical language from scratch outperforms models pre-trained on present-day
  language and later adapted to historical language.
url_dataset: ""
url_project: ""
publication_short: In *NLP4DH*
url_source: ""
url_video: ""
author_notes:
  - First autor
  - Second author
doi: ""
publication: In *NLP4DH workshop*
featured: true
tags: []
image:
  caption: "Image credit: MacBERTh team"
  focal_point: ""
  preview_only: true
date: "2021"
url_slides: ""
publishDate: 2021-12-01T00:00:00Z
url_poster: ""
url_code: ""
---

Evaluation code is available through [the project's repository](https://www.github.com/emanjavacas/macberth-eval). "MacBERTh" itself is available as **emanjavacas/MacBERTh** from the [transformers repository](https://huggingface.co/emanjavacas/MacBERTh) (Wolf et al. 2019).
