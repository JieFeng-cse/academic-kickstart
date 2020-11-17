---
title: "Hierarchical Large-scale Graph Similarity Computation via Graph Coarsening and Matching"
authors: ["Haoyan Xu", "Runjian Chen", "Yunsheng Bai", "Ziheng Duan", "Jie Feng", "Ke Luo", "Yizhou Sun", "Wei Wang"]
date: "2020-09-15"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Submitted to AAAI 2021

abstract: In this work, we focus on large graph similarity computation problem and propose a novel "embedding-coarsening-matching" learning framework, which outperforms state-of-the-art methods in this task and has significant improvement in time efficiency. Graph similarity computation for metrics such as Graph Edit Distance (GED) is typically NP-hard, and existing heuristics-based algorithms usually achieves a unsatisfactory trade-off between accuracy and efficiency. Recently the development of deep learning techniques provides a promising solution for this problem by a data-driven approach which trains a network to encode graphs to their own feature vectors and computes similarity based on feature vectors. These deep-learning methods can be classified to two categories, embedding models and matching models. Embedding models such as GCN-Mean and GCN-Max, which directly map graphs to respective feature vectors, run faster but the performance is usually poor due to the lack of interactions across graphs. Matching models such as GMN, whose encoding process involves interaction across the two graphs, are more accurate but interaction between whole graphs brings a significant increase in time consumption (at least quadratic time complexity over number of nodes). Inspired by large biological molecular identification where the whole molecular is first mapped to functional groups and then identified based on these functional groups, our "embedding-coarsening-matching" learning framework first embeds and coarsens large graphs to coarsened graphs with denser local topology and then matching mechanism is deployed on the coarsened graphs for the final similarity scores. Detailed experiments have been conducted and the results demonstrate the efficiency and effectiveness of our proposed framework.
# Summary. An optional shortened abstract.

tags:
- Source Themes
featured: false
profile: false
share: false

links:
- name: Custom Link
  url: https://arxiv.org/abs/2005.07115
url_pdf: https://arxiv.org/pdf/2005.07115.pdf

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'CosimGNN'
  focal_point: ""
  preview_only: false

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
#   Otherwise, set `slides: ""`.
slides: example
---



