---
title: My research experience and motivation
---
If you want to know more about my motivation and my researches, you are welcome to read. This blog is written in a casual style, and it will explain why I conducted the abovementioned researches as well as my motivation.

I have been obsessed with robots for a long time. When I was a kid, the *Transformer* literally blew my mind. I kept wondering, how could I make one of them, like, emmm, Bumblebee?  That is my initial motivation to join the robot club in high school and to choose Robotics track in college, where I first met a PR2, several UR5 and programmed one of them to wash pots. I know that is what I am willing to pursue, even though it could be difficult working with hardware.

My academic research began with a robot ontology, advised by Prof. Rong Xiong, who is an eminent roboticist.  The basic idea is to build a mechanism that a robot could automatically learn knowledge from demonstration, some vocal instruments might be needed. Then the knowledge will be stored in the ontology database, which would be used in further researches to utilize those knowledge guiding manipulators to conduct a series of actions with the given high-level commands, such as making a salad. Following the intuition of [FOON](https://arxiv.org/abs/1902.01537) (an IROS 2016 paper), I designed the ontology as a graph knowledge base so that a procedure for a salad, for instance, could be represented as a sub-graph, and searching could be easy with depth-first search aided with width-first search when the database is not too large, of course, a hash-table is built together with some mechanisms to avoid ambiguity.

I was completely fascinated by the idea that robot could learn by itself, although what we built was literally a pipeline that a robot could interact with human to instore the process of making a salad, the stored information includes features extracted from pictures of recorded ingredients, optical flow extracted from the demonstration video. It was pretty cool for a second year undergraduate as my small robot could generate a feasible procedure of making tuna salad with its "eyes" searching for what are available on the table, even though it could not really do this. So after that, my curiosity just keeps pushing me to solve a problem: how can I make it really do it? Which led to my incoming researches.

I have two major dissatisfaction with my prior project: (1) It can not infer. For example, even though it has knowledge about how to make a chicken chop, it could not know the procedure of  making a pork chop. They do share a lot in common. (2) It can not work for real manipulators. 

For the first problem, as my ontology database is built as a knowledge graph, it came up to me, why not try something with the Graph Neural Network? (The second reason is that I participated in our team for Robocup (ZJUNlict) for a short time and a PhD student encouraged me to use GNN to learn policies for football games, I quit because of the pandemic.) Then a senior undergraduate invited me to participate in a series of GNN projects, I did not hesitate to say yes. As he worked with Prof. [Yizhou Sun](http://web.cs.ucla.edu/~yzsun/) before, we chose Graph Matching as basic topic which we could gain help from a PhD student namely [Yunsheng Bai](http://yunshengb.com/), who did a great job on Graph Similarity Computation. As subgraphs represent specific activities in my ontology, I suggested that a partitioning process could be added before matching, the same intuition led to the "embedding-coarsening-matching" pipeline, which submitted to nips first, got a average of 5.5 because of insufficient experiments on public database, after we finished the required experiments, we resubmitted it to AAAI.

My partition paper was submitted to Neuralcomputing, the feedbacks look nice now. Then the co-authors marched towards MTS classification. I participated with some coding works, but not intensively.

Meanwhile, I was working on my internship at Tucodec, racing against time to compete in the CVPR Challenge on Learned Image Compression 2020, P-frame track. I joined the group because I think my computer vision skills are limited, and competition is a way people can learn the fastest. I worked there for five months and I think I have got some insights.

Then my journey of autonomous driving begins in July. I began the project with my own initiative, which have several traits: 
* Use GNN to embed relations between road-agents, a dynamic graph structure;
* Use LSTM to encode sequence information.

Then as I noticed SIREN, which was public and submitted to nips by then, I decided to use cosine as activation function and transfer the decoder to a Fourier transformation. This design makes the whole model get rid of LSTM and differentiable, which enables supervision on speed (I also tried ODE-net). However, the supervision on speed did not improve the performance significantly, and I gave up the project as the performance of Vector Net surpassed my model. Then I fully reproduced Vector net and TNT, which could help the researches proceeding in the MSC lab.

Man can never forget his original intention, that's why I contacted Prof. Yuke Zhu and began the project of grasping deformable objects. I think the project is challenging and charming. Without doubt, it is difficult and demanding as I need to begin from graphics and benchmarking a series of robot learning algorithms, but it gives me an opportunity to gain a panorama of robot learning. I hope I could develop some general-purpose learning models in the future, and push the boundary of technology. In order to achieve that goal, casualty inference, interpretability and safety are also the topics I am willing to pursue.

With the diary style description of my researches, I believe I have explained why I have conduct those projects and how my research interests developed. Sorry for my casual style of writing here, hope to meet you in my official sop again!







 





