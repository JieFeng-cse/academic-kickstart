---
​---
title: My research experience and motivation
date: 2020-11-20
math: true
diagram: true
​---
---
If you want to know more about my motivation and my researches, you are welcome to read.

I have been obsessed with robots for a long time. When I was a kid, the *Transformer* literally blew my mind. I kept wondering, how could I make one of them, like, emmm, Bumblebee?  That is my initial motivation to join the robot club in high school and to choose Robotics track in college, where I first met a PR2, several UR5 and programmed one of them to wash pots. I know that is what I am willing to pursue, even though it could be hard working with hardware.

My academic research began with a robot ontology, advised by Prof. Rong Xiong, who is an eminent roboticist.  The basic idea is to build a mechanism that a robot could automatically learn knowledge from demonstration, some vocal instruments might be needed. Then the knowledge will be stored as the ontology database, which would be used in further researches to utilize those knowledge to guide manipulators to conduct a series of movement with the given high-level commands, such as make a salad. Following the intuition of [FOON](https://arxiv.org/abs/1902.01537) (an IROS 2016 paper), I designed the ontology as a graph knowledge base so that a procedure for a salad, for instance, could be represented as a sub-graph, and searching could be easy with depth-first search aided with width-first search when the database is not too large, of course, a hash-table is built and some mechanisms to avoid ambiguity.

I was completely fascinated by the idea that robot could learn by itself, although what we built was literally a pipeline that a robot could interact with human to instore the process of making a salad, the stored information includes features extracted from pictures of recorded ingredients, optical flow extracted from the demonstration video. It was pretty cool for a second year undergraduate as my small robot could generate a feasible procedure for making a tuna salad with its "eyes" searching what are available, although it could not really do this. So after that, my curiosity just keeps pushing me, how can I make it really do it? Which led to my incoming researches.

I have two major dissatisfaction with my prior project: (1) It can not infer. For example, even though it has knowledge about how to make a chicken chop, it could not know the procedure of  making a pork chop. (2) It can not work for real manipulators. 

For the first problem, as my ontology database is built as a knowledge graph, it came up to me, why not try something with the Graph Neural Network? (The second reason is that I participated in our team for Robocup (ZJUNlict) for a short time and a PhD student encouraged me to use GNN to learn policies for football games, I quit because of the pandemic.) Then a senior undergraduate invited me to participate in





 





