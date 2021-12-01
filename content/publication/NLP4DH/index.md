---
title: "MacBERTh: Development and Evaluation of a  Historically Pre-trained Language Model for English (1450-1950)"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Enrique Manjavacas
- Lauren Fonteyn

# Author notes (optional)
author_notes:
- "First autor"
- "Second author"

date: "2021"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *NLP4DH workshop*
publication_short: In *NLP4DH*

abstract: The new pre-train-then-fine-tune paradigm in Natural Language Processing (NLP) has made important performance gains accessible to a wider audience. Once pre-trained, deploying a large language model presents comparatively small infrastructure requirements, and offers robust performance in many NLP tasks. The Digital Humanities (DH) community has been an early adapter of this paradigm. Yet, a large part of this community is concerned with the application of NLP algorithms to historical texts, for which large models pre-trained on contemporary text may not provide optimal results. In the present paper, we present "MacBERTh"---a transformer-based language model pre-trained on historical English---and exhaustively assess its benefits on a large set of relevant downstream tasks. Our experiments highlight that, despite some differences across target time periods, pre-training on historical language from scratch outperforms models pre-trained on present-day language and later adapted to historical language.

# Summary. An optional shortened abstract.
summary: This paper presents "MacBERTh", a transformer-based language model pre-trained on historical English, and exhaustively assess its benefits on a large set of relevant downstream tasks. Our experiments highlight that, despite some differences across target time periods, pre-training on historical language from scratch outperforms models pre-trained on present-day language and later adapted to historical language.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
