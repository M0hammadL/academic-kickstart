---
title: "Deep packet: a novel approach for encrypted traffic classification using deep learning
"
authors:
- Lotfollahi et al.
date: "2019-05-13"
doi: 
# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Nature Methods volume 16, pages715–721(2019)"
publication_short: ""

abstract: Network traffic classification has become more important with the rapid growth of Internet and online applications. Numerous studies have been done on this topic which have led to many different approaches. Most of these approaches use predefined features extracted by an expert in order to classify network traffic. In contrast, in this study, we propose a deep learning-based approach which integrates both feature extraction and classification phases into one system. Our proposed scheme, called “Deep Packet,” can handle both traffic characterization in which the network traffic is categorized into major classes (e.g., FTP and P2P) and application identification in which identifying end-user applications (e.g., BitTorrent and Skype) is desired. Contrary to most of the current methods, Deep Packet can identify encrypted traffic and also distinguishes between VPN and non-VPN network traffic. The Deep Packet framework employs two deep neural network structures, namely stacked autoencoder (SAE) and convolution neural network (CNN) in order to classify network traffic. Our experiments show that the best result is achieved when Deep Packet uses CNN as its classification model where it achieves recall of 0.98 in application identification task and 0.94 in traffic categorization task. To the best of our knowledge, Deep Packet outperforms all of the proposed classification methods on UNB ISCX VPN-nonVPN dataset.
# Summary. An optional shortened abstract.
summary:
tags:
- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://link.springer.com/article/10.1007/s00500-019-04030-2?wt_mc=Internal.Event.1.SEM.ArticleAuthorOnlineFirst

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---

