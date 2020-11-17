---
title: "Graph Partitioning and Graph Neural Network based Hierarchical Graph Matching for Graph Similarity Computation"
authors: ["Jie Feng*","Haoyan Xu*", "Ziheng Duan*", "Runjian Chen", "Qianru Zhang", "Yueyang Wang"]
date: "preprint"

# Schedule page publish date (NOT publication's date).
publishDate: "preprint"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Submitted to Neuralcomputing

abstract: Graph similarity computation aims to predict a similarity score between one pair of graphs so as to facilitate downstream applications, such as finding the chemical compounds that are most similar to a query compound or Fewshot 3D Action Recognition, \textit{etc}. Recently, some graph similarity computation models based on neural networks have been proposed, which are either based on graph-level interaction or node-level comparison. However, when the number of nodes in the graph increases, it will inevitably bring about the problem of reduced representation ability or excessive time complexity. Motivated by this observation, we propose a graph partitioning and graph neural network based model, called PSimGNN, to effectively resolve this issue. Specifically, each of the input graphs is partitioned into a set of subgraphs to directly extract the local structural features firstly. Next, a learnable embedding function is used to map each subgraph into an embedding vector. Then, some of these subgraph pairs are selected for node-level comparison to supplement the subgraph-level embedding with fine-grained information. Finally, coarse-grained interaction information among subgraphs and fine-grained comparison information among nodes in different subgraphs are integrated to predict the final similarity score. Using approximate Graph Edit Distance (GED) as graph similarity metric, experimental results on graph data sets of different graph size demonstrate PSimGNN outperforms state-of-the-art methods in graph similarity computation tasks. The codes will release when this paper is published.
# Summary. An optional shortened abstract.

tags:
- Source Themes
featured: true
profile: false
share: false

links:
- name: Custom Link
  url: https://arxiv.org/abs/2005.08008
url_pdf: https://arxiv.org/pdf/2005.08008.pdf

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**ICFNDS**](http://www.icfnds.org/)'
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



