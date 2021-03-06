---
title: "Language Model Pre-Training for Historical English: Approaches and Evaluation"
abstract: >
  Machine-based exploration of culturally relevant datasets (e.g. newspapers,
  periodicals, correspondence or annals) often involves understanding and
  processing historical texts. In this context, technology dealing with
  historical text needs to tackle a set of specific issues. First, historical
  corpora typically contain not only a variety of registers and genres, but also
  an unstable language with grammar and semantics in constant change. Secondly,
  the lack of orthographic standards that characterizes European languages prior
  to the 18th centuries implies a further aspect of variation on the linguistic
  form over which automated approaches need to abstract. Finally, in contrast to
  contemporary corpora that have been born already digitally, historical corpora
  must be digitized. Despite ongoing efforts to advance OCR and HTR technology,
  errors in the digitization pipeline constitute the last barrier.


  Current state-of-the-art approaches in Natural Language Processing (NLP) leverage the newly emerging pre-train-and-finetune paradigm, in which a large machine learning model is first trained in an unsupervised fashion on large datasets, and then fine-tuned on labelled data in order to perform a particular task of interest. This paradigm relies on variants of so-called Language Models—e.g. ELMO (Peters et al. 2018), BERT (Devlin et al. 2019) or GPT (Radford et al., 2018)—that can maximally exploit contextual cues in order to generate vectorized representations of given input tokens (e.g. words). At first sight, this paradigm may seem unrealistic for dealing with the three aspects of historical text mentioned above, since the notoriously large datasets that are needed in order to successfully pre-train such models are absent in the case of historical text. However, on-going efforts towards producing historically pre-trained Language Models (Hosseini et al. 2021), which leverage large databases of available text, have started to highlight the potential of this approach even for historical languages.


  With the goal of alleviating the data scarcity problem, previous research has leveraged contemporary Language Models (i.e. models pre-trained on contemporary data), using them as base models that are later fine-tuned on the target historical data in order to produce historically pre-trained models. While this approach may indeed help the model recognizing semantic relationships and linguistic patterns that are unchanged across time, it can also introduce an important bias in the vocabulary, which remains fixed to the vocabulary of the contemporary corpus.


  In this work, we aim to cast light onto both the merit of the pre-train-and-fine-tune paradigm for historical data, as well as the relative advantage of the different pre-training approaches (e.g. pre-training from scratch vs. adapting a pre-trained model). We focus on a large span of historical English text (date range: 1450-1950), presenting, first, the steps towards a newly pre-trained historical BERT, known as MacBERTh, which is trained on approx. 3B tokens of historical English. Secondly, we discuss a thorough evaluation, with a noted emphasis on lexical semantics, in which the capabilities of the different models for processing historical text are put to test.


  In order to do so, we elaborate a number of historically relevant benchmark tasks extracted from the Oxford English Dictionary, relying on the diachronic word sense classifications and the example quotations used for exemplifying the word senses.


  In particular, we evaluate the different approaches on tasks that require systems to incorporate a model of word senses as well as a founded understanding of sentential semantics. In total, we present results for three different tasks, including Word Sense Disambiguation (WSD) from two different angles, Text Periodization and an ad-hoc Fill-In-The-Blank task that indirectly captures aspects of Natural Language Understanding.


  Our evaluation highlights that, indeed, models originally pre-trained on contemporary English may also import too strong an inductive bias when they are later fine-tuned on historical English. In such a situation, pre-training from scratch on historical data may be a more robust strategy than adapting a pre-trained model.


  With this work, we hope to assist Digital Humanities scholars willing to fine-tune and deploy NLP models on their own historical collections, as well as researchers who may be working on developing similar models and resources for other historical (and possibly non-European) languages.
location: Tokyo (Online conference only)
date: 2022-07-27T05:00:50.821Z
date_end: 2022-07-27T06:30:00.000Z
all_day: false
event: DH2022
event_url: https://dh2022.adho.org/program/presentations
publishDate: 2022-06-13T14:14:50.839Z
draft: false
featured: false

links:
url_code: ""
url_pdf: ""
url_slides: "https://docs.google.com/presentation/d/1LkhdhNYv95Rf75lxh7Cg23xDBEGjtiPQB3uIMvIcRhA/edit?usp=sharing"
url_video: "https://surfdrive.surf.nl/files/index.php/s/aQLkhz5uBZOwI2X"

image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
