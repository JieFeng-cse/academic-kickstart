---
title: "Parallel Extraction of Long-term Trends and Short-term Fluctuation Framework for Multivariate Time Series Forecasting"
authors: [Haoyan Xu, Ziheng Duan, Yida Huang, Jie Feng, Anni Ren, Qianru Zhang, Pengyu Song, Xiaoqian Wang]
date: "2020-09-07T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "preprint"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Submitted to AAAI 2021

abstract: Multivariate time series forecasting is widely used in various fields. Reasonable prediction results can assist people in planning and decision-making, generate benefits and avoid risks. Normally, there are two characteristics of time series, that is, long-term trend and short-term fluctuation. For example, stock prices will have a long-term upward trend with the market, but there may be a small decline in the short term. These two characteristics are often relatively independent of each other. However, the existing prediction methods often do not distinguish between them, which reduces the accuracy of the prediction model. In this paper, a MTS forecasting framework that can capture the long-term trends and short-term fluctuations of time series in parallel is proposed. This method uses the original time series and its first difference to characterize long-term trends and short-term fluctuations. Three prediction sub-networks are constructed to predict long-term trends, short-term fluctuations and the final value to be predicted. In the overall optimization goal, the idea of multi-task learning is used for reference, which is to make the prediction results of long-term trends and short-term fluctuations as close to the real values as possible while requiring to approximate the values to be predicted. In this way, the proposed method uses more supervision information and can more accurately capture the changing trend of the time series, thereby improving the forecasting performance.
# Summary. An optional shortened abstract.

tags:
- Source Themes
featured: false
profile: false
share: false

links:
- name: Custom Link
  url: https://arxiv.org/abs/2008.07730
url_pdf: https://arxiv.org/pdf/2008.07730.pdf

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
  #caption: 'Image credit: [**ICFNDS**](http://www.icfnds.org/)'
  #focal_point: ""
  #preview_only: false

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



