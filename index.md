---
layout: default
title: Natural Language Processing
nav_order: 1
permalink: /
---

# Natural Language Processing
{: .fs-10 }

Mario Graff (mgraffg en ieee.org)
{: .fs-7 }


---

# Introduction

In our daily life, we use applications based on Natural Language Processing (NLP) techniques. It is common to use a virtual assistant such as Siri or Alexa or call a call center where the options are selected orally, or even use the dictation service of the mobile. When visiting a foreign country or learning another language is common to use the service of an online translation system, e.g., Google Translate. Other NLP applications might not be as evident as the ones mentioned. For example, Twitter suggests following a conversation based on the topic. Grammarly helps in the writing style; this can also be done with Word and Google Docs options. On the other hand, there are NLP applications developed to eliciting information from opinions expressed on social media or the web.

The goal of the course is to introduce the students to the field of Natural Language Processing. The most relevant NLP applications will be described through lectures, reading, and programming activities; these include collocations, language models, text categorization, word embeddings, question answering, and sentence entailment, among others.

# Notation

|Symbol            | Meaning                      |
|------------------|------------------------------|
|$$x$$             | Variable $$x \in \mathbb R$$ |
|$$\mathbb R$$     | The real numbers             |
|$$\mathbf x$$     | Vector $$\mathbf x \in \mathbb R^d$$ |
|$$d$$             | Dimension                    |
|$$\mathbf w \cdot \mathbf x$$ | Dot product    |
|$$N$$             | Number of examples           |
|$$K$$             | Number of classes or labels  |
|$$\mathbb 1(e)$$  | Indicator function; one only if $$e$$ is true |

#  Requirements

## Python's Libraries

- [NumPy](https://numpy.org)
- [scikit-learn](https://scikit-learn.org/stable/index.html)
- [spacy](https://spacy.io)
- [$$\mu$$TC](https://microtc.readthedocs.io/en/latest/)
- [EvoMSA](https://evomsa.readthedocs.io/en/latest/)

# Bibliography

- Introduction to machine learning, Third Edition. Ethem Alpaydin. MIT Press
- All of Statistics. A Concise Course in Statistical Inference. Larry Wasserman. MIT Press.
