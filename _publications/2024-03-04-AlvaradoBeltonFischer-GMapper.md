---
layout: single-publication

author: "Sourabh Palande"

title: "<i>G-Mapper</i>: Learning a Cover in the Mapper Construction"

collection: publications

pubtype: "Preprint"

permalink: /publication/2024-03-04-AlvaradoBeltonFischer-GMapper

excerpt: 'We present a G-means clustering-based algorithm that optimizes the cover of a Mapper graph by iteratively splitting it using the Anderson-Darling test of normality.'

date: 2024-03-04

venue: 'ArXiv preprint [cs.LG]'

pdflink: 'http://sourabhpalande.github.io/files/AlvaradoBeltonFischer2024-GMapper.pdf'

paperurl: 'https://arxiv.org/abs/2309.06634'

citation: 'Enrique Alvarado, Robin Belton, Emily Fischer, Kang-Ju Lee, et al. "$G$-Mapper: Learning a Cover in the Mapper Construction." ArXiv [cs.LG], 2024.'

token: "gmapper.png"

abstract: 'The Mapper algorithm is a visualization technique in topological data analysis (TDA) that outputs a graph reflecting the structure of a given dataset. However, the Mapper algorithm requires tuning several parameters in order to generate a "nice" Mapper graph. This paper focuses on selecting the cover parameter. We present an algorithm that optimizes the cover of a Mapper graph by splitting a cover repeatedly according to a statistical test for normality. Our algorithm is based on G-means clustering which searches for the optimal number of clusters in k-means by iteratively applying the Anderson-Darling test. Our splitting procedure employs a Gaussian mixture model to carefully choose the cover according to the distribution of the given data. Experiments for synthetic and real-world datasets demonstrate that our algorithm generates covers so that the Mapper graphs retain the essence of the datasets, while also running significantly fast.'

---
