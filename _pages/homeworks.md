---
layout: archive
title: "Homework Projects"
permalink: /homeworks/
author_profile: true
---

{% include base_path %}
# Homework projects
During the Masters degree there are many projects that had to be done for the different courses, here is a selection of those:
## Advanced machine learning
A part of the course [advanced machine learning](https://ml2.inf.ethz.ch/courses/aml/) are the four tasks that have to be completed:
- [Task1](https://github.com/lblum95/AML/tree/master/task1) which tackles outlier detection, feature selection and data cleaning.
- [Task2](https://github.com/lblum95/AML/tree/master/task2) where again feature selection and class imbalance are the problem.
## Advanced systems lab project
The objective of the [advanced systems lab](https://acl.inf.ethz.ch/teaching/fastcode/2020/) is to design, write and evaluate fast C code. As a test of our abilities we have to write a [project](https://github.com/rostro36/Baum-Welch). Our group decided on the [Baum-Welch algorithm](https://en.wikipedia.org/wiki/Baum%E2%80%93Welch_algorithm), which is a special case of the expectation-maximization algorithm of hidden Markov models. As part of the project, our group reordered the steps of the EM-algorithm, unrolled loops, inserted SIMD instructions and checked the performance in valgrind.
## Computational intelligence lab project
One main focus of the [computational intelligence lab](http://www.da.inf.ethz.ch/teaching/2020/CIL/) is how to model data (images, text, etc.). Part of the course is a project, where we chose the task of [sentiment analysis of tweets](https://github.com/berniwal/CIL_Project/tree/master/CIL). We tried out [BERT](https://github.com/google-research/bert), [ALBERT](https://github.com/google-research/albert) of different sizes and also lexical normalization with [MoNoise](http://www.let.rug.nl/rob/doc/clin27.paper.pdf).
## Machine learning for healthcare
The course [machine learning for healthcare](https://bmi.inf.ethz.ch/teaching/261-5120-00l-machine-learning-for-health-care-spring-2020/) reviews most relevant methods and applications of machine learning in biomedicine. To get hands-on experience we did some projects.
- [Task1](https://github.com/rostro36/ML4HC-HW1) does a heartbeat classification with [keras](https://keras.io/) neural nets, that also uses transfer learning.
- Task2 is split in two parts:
	- The [first part](https://github.com/rostro36/ML4HC_task1) is about classifying clinical notes to the sickness that they describe.
	- The [second part](https://github.com/rostro36/ML4HC-KaggleTask) was not finished, but tried to use "pre-seeded" [LDA](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation) to search desired articles.
- [Task3](https://github.com/rostro36/ML4HC-HW3) uses [U-Net](https://lmb.informatik.uni-freiburg.de/people/ronneber/u-net/) to segment CT scans.
## Partisan responses
For the course [Sequencing Legal DNA](http://www.vvz.ethz.ch/Vorlesungsverzeichnis/lerneinheit.view?semkez=2020S&ansicht=KATALOGDATEN&lerneinheitId=134877&lang=en) we had to do a course project. Our group decided on the [big project](https://github.com/rostro36/Partisan-Responses/) of generating partisan responses based on U.S. congressional speeches.

The subtask for this project were:
- Filtering and pre-process the dataset.
- Search related speeches in the dataset based on a query
- Extract information from the resulting dataset using [AllenNLPs module](https://demo.allennlp.org/open-information-extraction)
- Use that information to build knowledge graphs
- Generate responses based on those knowledge graphs using [GraphWriter](https://github.com/rikdz/GraphWriter/)

Since that pipeline did not work out as hoped and to baseline, we also tested the text generation capabilities of [GPT-2](https://github.com/openai/gpt-2).
# Notes
In my second semester it dawned on me, that I could keep the notes of the mandatory lecture  on computer instead of my bad handwriting.
## [Big data](https://github.com/rostro36/Notes/tree/master/Big%20Data/)
There are many mandatory readings for the course [big data](https://systems.ethz.ch/education/courses/2020-fall//big-data.html).

Here is a selection of readings:
- [Dynamo: Amazon’s Highly Available Key-value Store](http://doi.org/10.1145/1294261.1294281)
- [Windows Azure Storage: A Highly Available Cloud Storage Service with Strong Consistency](https://sigops.org/s/conferences/sosp/2011/current/2011-Cascais/printable/11-calder.pdf)
- [Dremel: Interactive Analysis of Web-Scale Datasets](https://doi.org/10.1145/1953122.1953148)
- [JSON ECMA standard](https://www.ecma-international.org/publications/files/ECMA-ST/ECMA-404.pdf)
- [Understanding JSON Schema](https://json-schema.org/understanding-json-schema/)
- [XML in a Nutshell](https://www.oreilly.com/library/view/xml-in-a/0596007647/)
- [HBase: The Definitive Guide](https://www.oreilly.com/library/view/hbase-the-definitive/9781449314682/)
- [Bigtable: A Distributed Storage System for Structured Data](https://research.google.com/archive/bigtable-osdi06.pdf)
- [Hadoop: The Definitive Guide](https://www.oreilly.com/library/view/hadoop-the-definitive/9780596521974/)
- [The Hadoop Distributed File System](https://doi.org/10.1109/MSST.2010.5496972)
## [Learning group](https://github.com/rostro36/Notes/tree/master/Learning%20group)
The [natural language lab of ETH](rycolab.github.io/) has a weekly [learning group](https://rycolab.github.io/readinggroup/) that discusses interesting papers.

Here are some that I have read:
- [Learning Sparse Networks Using Targeted Dropout](https://arxiv.org/pdf/1905.13678.pdf)
- [Variational dropout](https://papers.nips.cc/paper/5666-variational-dropout-and-the-local-reparameterization-trick)
