---
title: "Using indication embeddings to represent patient health for drug safety studies"
authors:
- Melamed R
#date: "2020-03-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
#publication_types: ["1"]

# Publication name and optional abbreviated publication name.
# publication: In *Source Themes Conference*
publication_short: In *STC*

abstract: A popular approach to discovering previously unknown effects of drugs is the cohort study. In cohort studies, experts carefully craft a control population and compare the rates of some adverse outcome in the treated people against that control population. To expand the cohort study method, I used neural networks approaches to help automatically identify a good control population, avoiding the need for expert design.

# Summary. An optional shortened abstract.
summary: A major goal of my research is to discover effects of drugs using large medical data. In this work, I use neural network methods to create a better way to summarize health care data in order to discover these effects. 

#tags:
#- Source Themes
featured: true

links:
- name: JAMIA Open
  url: https://academic.oup.com/jamiaopen/advance-article/doi/10.1093/jamiaopen/ooaa040/5940801
url_pdf: "files/Melamed-2020-Indication embeddings.pdf"
url_code: 'https://github.com/RDMelamed/indication-embeddings'
#url_dataset: '#'
url_poster: 'files/poster_melamed_amianov.pdf' 
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: 'https://youtu.be/VAhRQ7QHMqA'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`. ![featured.png](detailed.png)
slides: example
---

[<img src="Slide1.jpeg" alt="poster" vspace = "20" width="350" height="350" align="center" />](/files/poster_melamed_amianov.pdf)

Methods to discover effects of drugs in health data must account for tens of thousands of potentially relevant confounders. Our goal in this work is to reduce the dimensionality of the health data with the aim of accelerating the application of retrospective cohort studies to this data.

In this work, we develop indication embeddings, a way to reduce the dimensionality of health data while capturing the information relevant to treatment decisions. We evaluate these embeddings using external data on drug indications. Then, we use the embeddings as a substitute for medical history to match patients, and develop evaluation metrics for these matches.

We demonstrate that these embeddings recover therapeutic uses of drugs. We use embeddings as an informative representation of relationships between drugs, between health history events and drug prescriptions, and between patients at a particular time in their health history. We show that using embeddings to match cohorts improves the balance of the cohorts in terms of poorly measured risk factors like smoking.

Unike other embeddings inspired by word2vec, indication embeddings are specifically designed to capture the medical history leading to prescription of a new drug. For retrospective cohort studies, our low-dimensional representation helps in finding comparator drugs and constructing comparator cohorts.




