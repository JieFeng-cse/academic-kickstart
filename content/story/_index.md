---
# Display name
title: Jie Feng

# Username (this should match the folder name)
authors:
- admin

# Is this the primary user of the site?
superuser: true

# Role/position
role: Senior Student

# Organizations/Affiliations
organizations:
- name: Zhejiang University
  url: "http://www.zju.edu.cn/english/"
- email: zjucse_fj@zju.edu.cn

education:
  courses:
  # - course: PhD in Artificial Intelligence
  #   institution: Stanford University
  #   year: 2012
  - course: Research Assistant, advised by Prof. Tomizuka 
    institution: University of California, Berkeley
    year: 2020
  - course: BSc in Control Science and Engineering, advised by Prof. Rong Xiong
    institution: Zhejiang University
    year: 2017-2021

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
- icon: envelope
  icon_pack: fas
  link: "mailto:zjucse_fj@zju.edu.cn"  # For a direct email link, use "mailto:test@example.org".
- icon: twitter
  icon_pack: fab
  link: https://twitter.com/jiefengcse
# - icon: google-scholar
#   icon_pack: ai
#   link: https://scholar.google.co.uk/citations?user=sIwtMXoAAAAJ
- icon: github
  icon_pack: fab
  link: https://github.com/JieFeng-cse
# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
- icon: cv
  icon_pack: ai
  link: files/cv.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: "zjucse_fj@zju.edu.cn"

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
# user_groups:
# - Researchers
# - Visitors
---
Hi, I am Jie Feng, a senior undergraduate student in Zhejiang University.

I study in the Mixed Honor Class in Chu Kochen Honors College at Zhejiang University, an Honor Program for top 5% students at Zhejiang University. 

My major is Control Science and Engineering and I am advised by Prof. [Rong Xiong](https://person.zju.edu.cn/en/rongxiong#776514). I am also a research assistant in [MSC lab](https://msc.berkeley.edu/), working closely with Prof. [Tomizuka](https://me.berkeley.edu/people/masayoshi-tomizuka/), Post Doc. [Wei Zhan](https://scholar.google.com/citations?user=xVN3UxYAAAAJ&hl=en) and Post Doc. [Liting Sun](https://scholar.google.com/citations?hl=en&user=BitIg-YAAAAJ&view_op=list_works&sortby=pubdate). Previously, I worked as a research intern at [Tucodec](https://www.tucodec.com/) and won CVPR CLIC 2020 championship in P-frame track.

In the next few months, I am fortune to have the opportunity to work closely with Prof. [Yuke Zhu](https://www.cs.utexas.edu/~yukez/). 

I am looking for a PhD position enrolled in fall 2021, and my CV is on the left. I am actively seeking for collaborations and opportunities. Feel to reach out if you are interested in my research.

Research Interests:

* Unsupervised or semi-supervised robot learning methods
* Interpretable models, especially for planning
* Representation learning, Graph Neural Networks

PS: A general and unofficial description of my research experience and motivation (take it like a personal confession, if you are not interested, please skip to next section)

I have been obsessed with robots for a long time. When I was a kid, the *Transformer* literally blew my mind. I kept wondering, how could I make one of them, like, emmm, Bumblebee?  That is my initial motivation to join the robot club in high school and to choose Robotics track in college, where I first met a PR2, several UR5 and programmed one of them to wash pots. I know that is what I am willing to pursue, even though it could be hard working with hardware.

My academic research began with a robot ontology, advised by Prof. Rong Xiong, who is an eminent roboticist.  The basic idea is to build a mechanism that a robot could automatically learn knowledge from demonstration, some vocal instruments might be needed. Then the knowledge will be stored as the ontology database, which would be used in further researches to utilize those knowledge to guide manipulators to conduct a series of movement with the given high-level commands, such as make a salad. Following the intuition of [FOON](https://arxiv.org/abs/1902.01537) (an IROS 2016 paper), I designed the ontology as a graph knowledge base so that a procedure for a salad, for instance, could be represented as a sub-graph, and searching could be easy with depth-first search aided with width-first search when the database is not too large, of course, a hash-table is built and some mechanisms to avoid ambiguity.

I was completely fascinated by the idea that robot could learn by itself, although what we built was literally a pipeline that a robot could interact with human to instore the process of making a salad, the stored information includes features extracted from pictures of recorded ingredients, optical flow extracted from the demonstration video. It was pretty cool for a second year undergraduate as my small robot could generate a feasible procedure for making a tuna salad with its "eyes" searching what are available, although it could not really do this. So after that, my curiosity just keeps pushing me, how can I make it really do it? Which led to my incoming researches.

I have two major dissatisfaction with my prior project: (1) It can not infer. For example, even though it has knowledge about how to make a chicken chop, it could not know the procedure of  making a pork chop. (2) It can not work for real manipulators. 

For the first problem, as my ontology database is built as a knowledge graph, it came up to me, why not try something with the Graph Neural Network? (The second reason is that I participated in our team for Robocup (ZJUNlict) for a short time and a PhD student encouraged me to use GNN to learn policies for football games, I quit because of the pandemic.) Then a senior undergraduate invited me to participate in





 





