---
title: "[PRE-PRINT] Adapting vs Pre-training Language Models for Historical Languages"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Enrique Manjavacas
- Lauren Fonteyn

# Author notes (optional)
author_notes:
- "First autor"
- "First author"

date: "2022"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *HAL Open Science*
publication_short: In *HAL*

abstract: As large language models such as BERT are becoming increasingly popular in Digital Humanities (DH), the question has arisen as to how such models can be made suitable for application to specific textual domains, including that of ‘historical text’. Large language models like BERT can be pretrained from scratch on a specific textual domain and achieve strong performance on a series of downstream tasks. However, this is a costly endeavour, both in terms of the computational resources as well as the substantial amounts of training data it requires. An appealing alternative, then, is to employ existing ‘general purpose’ models (pre-trained on present-day language) and subsequently adapt them to a specific domain by further pre-training. Focusing on the domain of historical text in English, this paper demonstrates that pre-training on domain-specific (i.e. historical) data from scratch yields a generally stronger background model than adapting a present-day language model. We show this on the basis of a variety of downstream tasks, ranging from established tasks such as Part-of-Speech tagging, Named Entity Recognition and Word Sense Disambiguation, to ad-hoc tasks
like Sentence Periodization, which are specifically designed to test historically relevant processing.

# Summary. An optional shortened abstract.
summary: This paper is a pre-print. Please use and cite the published version as soon as it is available. Focusing on the domain of historical text in English, this paper demonstrates that pre-training on domain-specific (i.e. historical) data from scratch yields a generally stronger background model than adapting a present-day language model. We show this on the basis of a variety of downstream tasks, ranging from established tasks such as Part-of-Speech tagging, Named Entity Recognition and Word Sense Disambiguation, to ad-hoc tasks like Sentence Periodization, which are specifically designed to test historically relevant processing.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://hal.inria.fr/hal-03592137/document'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: MacBERTh team'
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

Evaluation code is available through [the project's repository](https://www.github.com/emanjavacas/macberth-eval). "MacBERTh" itself is available as **emanjavacas/MacBERTh** from the [transformers repository](https://huggingface.co/emanjavacas/MacBERTh) (Wolf et al. 2019).
