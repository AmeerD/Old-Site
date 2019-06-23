---
title: Ameer's Site
description:  Hello there! Welcome to my personal site!
---

## About Me

Hello! My name is Ameer, I'm a recent graduate from the University of Waterloo with a Bachelor of Mathematics. While at UW, I studied a wonderful mix of statistics, computer science and finance with a little physical science thrown in for fun. My experiences over the past few years have led me to develop a keen interest in computational statistics and machine learning. I have had the opportunity to partake in projects and extra curricular activities involving computer vision, text mining, venture capital, and predictive modelling with financial data. Keep reading to learn a little more about my academic and professional experiences.

--Ameer


## Projects

### CSEye

March 2018 - September 2018

Conference: AAAI-2019 Student Abstract Category

The final camera-ready draft of the paper, *CSEye: A Proposed Solution for Accurate and Accessible One-to-Many
Face Verification*, can be found [here](./CSEye_AAAI_2019_SA_412_CRC.pdf).

CSEye is a low-cost, one-to-many facial verfication model that addresses the one-to-many verification process using a unique, three-stage model architecture. First, a truncated VGG19 network extracts features from the suspect image and the candidate images. We then vectorize the extract feature matrices and compute sets of differences based on angle, dot product and element-wise distance measures. Finally, a dense network selects the optimal suspect-candidate match. CSEye was trained on randomly generated suspect-candidate sets from the [Labelled Faces in the Wild](http://vis-www.cs.umass.edu/lfw/) dataset. The angle and distance measures reliably produce accuracy rates exceeding 90% in initial tests with the angle measure reporting accuracies up to 98%. 

The idea behind CSEye was inspired by the final project for Winter 2018 *STAT 841 - Statistical Learning - Classification*. We were challenged to develop a novel classification algorithm and demonstrate it's ability in some domain. My team of three other students and myself decided to create a computer vision model addressing the problem of one-to-many face verification in a low-cost approach without compromising on accuracy. In this project we extracted weights from the suspect and all candidate images with a CNN that employed a weight-sharing scheme. This structure ensured identical treatment of all images. The suspect features are then injected into a dense network as weights to influence the suspect-candidate match. This structure facilitates the interaction between the suspect weights and the candidate weights in the layer preceeding final classification. The [draft](http://rosiezou.com/441proj.html) of the initial CSEye project provides a description of the model architecture and approach. The [Jupyter notebook](https://github.com/rosiezou/cvproj/blob/master/441proj.ipynb) containing the model and the [github repository](https://github.com/rosiezou/cvproj) are available for viewing. 

### Gadsby Text Mining

September 2017 - June 2018

Having thoroughly enjoyed *STAT 442 - Data Visualization* in Fall 2016, I approached Professor Wayne Oldford upon returning to university the following Fall semester to work on a project together. After discussing interesting datasets available and thinking about what may be useful from a curriculum perspective, we settled on a text mining project. We decided to perform a decomposition of the book *Gadsby* by Ernest Vincent Wright. *Gadsby* is known as *A Story of Over 50,000 Words Without Using the Letter "E"*. This interesting quirk was the perfect starting point for analysis.

*Gadsby*'s raw text was extracted from [Wikisource](https://en.wikisource.org/wiki/Gadsby) and then pre-processed using [tidytext principles](https://www.tidytextmining.com/index.html). The text is decomposed on a character, word and bi-gram basis. We then analyze the frequencies of each of the decompositions to identify patterns in writing stype and to verify the book's claim to fame (Spoiler Alert: There are actually 4 letter "E"'s). It is quite interesting to note that the author avoids using the word "the" by referencing objects indirectly using the word "a" and taking steps to identify which specific object is being referenced. We then considered additional features such as the tf-idf statistic, basic sentiment analysis and considered a probabilistic approach to letter frequency as a thought experiment. The results are summarized in a series of visualizations in report format.

The [final report](./Gadsby_Project.html) discusses the process, findings, and learning outcomes of the Gadsby project. The RMarkdown file used to generate the report along with the associated R code can be found [here](https://github.com/AmeerD/Gadsby).


## Work Experiences (in construction)

### Omnia AI


### ONEX


## Other Activities (in construction)

### Student Venture Fund

### Student Investment Fund
