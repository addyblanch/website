---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Large expert-curated database for benchmarking document similarity detection
  in biomedical literature search
subtitle: ''
summary: ''
authors:
- Peter Brown
- RELISH Consortium
- Yaoqi Zhou
tags: []
categories: []
date: '2019-01-01'
lastmod: 2021-01-13T13:38:20Z
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-01-13T13:38:20.314632Z'
publication_types:
- '2'
abstract: Document recommendation systems for locating relevant literature have mostly
  relied on methods developed a decade ago. This is largely due to the lack of a large
  ofﬂine gold-standard benchmark of relevant documents that cover a variety of research
  ﬁelds such that newly developed literature search techniques can be compared, improved
  and translated into practice. To overcome this bottleneck, we have established the
  RElevant LIterature SearcH consortium consisting of more than 1500 scientists from
  84 countries, who have collectively annotated the relevance of over 180 000 PubMed-listed
  articles with regard to their respective seed (input) article/s. The majority of
  annotations were contributed by highly experienced, original authors of the seed
  articles. The collected data cover 76% of all unique PubMed Medical Subject Headings
  descriptors. No systematic biases were observed across different experience levels,
  research ﬁelds or time spent on annotations. More importantly, annotations of the
  same document pairs contributed by different scientists were highly concordant.
  We further show that the three representative baseline methods used to generate
  recommended articles for evaluation (Okapi Best Matching 25, Term Frequency–Inverse
  Document Frequency and PubMed Related Articles) had similar overall performances.
  Additionally, we found that these methods each tend to produce distinct collections
  of recommended articles, suggesting that a hybrid method may be required to completely
  capture all relevant articles. The established database server located at https://relishdb.ict.grifﬁth.edu.au
  is freely available for the downloading of annotation data and the blind testing
  of new methods. We expect that this benchmark will be useful for stimulating the
  development of new powerful techniques for title and title/abstract-based search
  engines for relevant articles in biomedical research.
publication: '*Database*'
---
