---
layout: default
title: Pages
---

<style>
ul {
    list-style-type: square;
    padding-left: 10px;
}
li {
    margin: 0 0 0 5px;
}
p { display: inline; }
</style>

## Education
October 2018 - current    
M.Sc., Computer Science, Saarland University, Germany  
Field: ML, NLP, Deep Learning  

<br/><br/>
September 2014 - June 2018  
B.Eng., Computer Science and Technology, BUPT, China  
**Thesis**: *Research and Design on Automatic Composing System of Jiangsu Folk Songs Based on Machine Learning*  

<br/><br/>
<br/><br/>
## Internships
Oct 2021 - Oct 2022, JD.com  
Participated in mostly data retrieval tasks and the product category prediction optimization of queries.  
**SEO with medical queries**
- During shopping season, used SQL to retrieve data and analyzed critical advertising benchmarks e.g. UV, CTR, CVR, GMV, etc.
- Learned about the usage of company database platform,  got familiar with procedure of how to create routine data retrieval tasks, and gained some experience with Spark
- Learned about construction of medical knowledge graphs
- Used knowledge graphs to complete the first phase in optimization of product category prediction of given queries, by A/B testing witnessed improvement of GMV
- Made research of using deep learning model to do the optimization and found a proposed DNN+GBDT model, used Pytorch to implement the model

<br/>
Jan 2022 - June 2022, Siemens   
The team focuses on software development for various IoT devices. This project is about to utilize an AGV (Automated Guided Vehicle) to provide on-demand delivery services within an office area. I worked on the navigation and IoT integration aspects of the project.  
**AGV Navigation Optimization**
- Explored ROS documentation to optimize the navigation algorithm  
- Did research on planning algorithms in ROS, including global and local planning. Selected Dijkstra algorithm for global planning and utilized Time Elastic Band (TEB) for local planning  
- Implemented AGV movement, resolving issues such as turning, parallel movement, and handling moving obstacles  
- Resolved problems by analyzing source code, adjusting ROS parameters, and adding additional functionality

**Integration with IOT2050**
- Due to the AGV's navigation requirements and resource consumption, it was necessary to use an intermediate device to handle other tasks. Integrated the AGV into the Siemens IOT system using the IOT2050 device  
- Configured the gateway and utilized the provided Edge Connect gateway service to send internal AGV data to the IOT2050 device, where messages were then forwarded to the cloud via the IOT2050 device  

<br/><br/>
## Projects
**Neural Machine Translation for Bangla and English**  
June 2020 - Oct 2020  
Machine translation task between Bangla language and English in Python
- Select dataset from GlobalVoices and OPUS
- Use convolutional seq2seq as training and translation model, evaluate model using BLEU score
- After 100 Epoch, get loss score 0.0194, and for translation part have BLEU score 0.68

**Fake Face Detection and Model Attack**  
June 2019 - Aug 2019  
Defense against *DeepFake*, using deep learning methods to detect forged human facial data in Python 
- Use FaceForencis++ as dataset, CelebA as extra test set
- Use CNN model: 3\*3 convolutional layers, ReLU function, 2\*2 max-pooling layers
- Get 90% accuracy on basic dataset
- In order to increase the generality of model, use fine tuning. After 2 Epochs, raise 5% accurary on CelebA

**Compiler for subset of C, written in C++**  
October 2018 - January 2019  
Compiler for the subset of C language, implemented by C++
- lexical analysis: tokenize source code
- syntactic analysis: use LL(1) grammars to parse tokens
- semantic analysis: generate a AST tree

**Pokemon Game for C++ programming**  
October 2016 - January 2017  
The project based on the original game Pokemon, using Qt and developed in Windows 10 environment 
- Use classes to store informations of Pokemon
- Use Client-Server Model to implement sign up/login with Socket between client and server. Store client data on database (MSDB).    
- Design the animation effect of battle between Pokemons with Qt user interface.
