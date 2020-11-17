+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Research Intern"
  company = "TuCodec"
  company_url = "https://www.tucodec.com/"
  location = "Shanghai"
  date_start = "2020-01-14"
  date_end = "2020-06-14"
  description = """
  Responsibilities include:
  * Designed a novel end-to-end video compression framework with joint motion vector and residual prediction for P-frame tasks, and the prior probability of the representations are modeled by a hyperprior autoencoder

  *  Participated in the CVPR CLIC 2020. Our framework achieve the highest MS-SSIM performance for P-frame task in both validation phase and test phase
"""

[[experience]]
  title = "Research Assistant"
  company = "University of California, Berkeley"
  company_url = ""
  location = "MSC lab, remote, supervised by Prof. Tomizuka"
  date_start = "2020-07-04"
  date_end = "2020-12-01"
  description = """
  * Proposed a novel GNN architecture which incorporates attention mechanism based on agents' distance and speeds. This framework could model interaction between road agents and update features

  * Implemented ODE-net for trajectory fitting, which could learn better sequential information and generate robust and differentiable results

  *  Reproduced Vector net and tested its performance under different levels of uncertainty.
  
    """

[[experience]]
  title = "Research Assistant"
  company = "University of Texas at Austin"
  company_url = ""
  location = "Supervised by Prof. Yuke Zhu"
  date_start = "2020-11-04"
  date_end = "2021-06-01"
  description = """

  * Design a benchmark for grasping deformable objects

  * A systematical project starts from Mujoco engine, finish graphics work and then benchmarking main-stream robot learning methods. 

    """

+++
