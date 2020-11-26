---
title: "Visualizing Transfer Learning in COVID-19 X-rays"
layout: post
date: 2020-11-25 19:28  
image: /assets/images/HMS_DBMI_Logo.svg
headerImage: True
projects: true
tag:
- Transfer Learning
- Deep Learning
- Machine Learning
- Healthcare
- Radiology
- X-rays
star: true
category: project
author: Matthew West
description: Research Project BMI 707 Deep Learning for Biomedical Data
mathjax: True
---

Ever wondered what a convolutional neural network 'sees' when it makes predictions about the class of a given image? Visualizations of individual neurons within a network can, with a few tricks, reveal the kinds of features learnt by that network, [and provide some pretty compelling visualizations, too.](https://distill.pub/2017/feature-visualization/)

For applications of computer vision to healthcare, it's especially important that these learnt features are actually related to the diagnosis and not simply technical artifacts of the imaging process. Transfer learning for vision tasks in medicine typically involves using networks pre-trained on ImageNet, which [may not always provide features that are generalizable to problems in medicine,](https://ai.googleblog.com/2019/12/understanding-transfer-learning-for.html), despite often converging on valid representations. When they do converge, it doesn't appear to be to due to useful feature re-use, with random initialization providing comparable results. 

This project applies the paradigm of transfer learning to a [public dataset of COVID-19 X-rays](https://github.com/ieee8023/covid-chestxray-dataset), compiled by Joseph Paul Cohen and a team at the University of Montreal. In doing so, I've aimed to visualize the types of features learnt by networks pre-trained on ImageNet, as well as providing a comparison to both models trained from scratch, and to those pre-trained on [CheXNet](https://stanfordmlgroup.github.io/projects/chexnet/), a DenseNet architecture initally trained on the [ChestX-ray14 dataset.](https://www.nih.gov/news-events/news-releases/nih-clinical-center-provides-one-largest-publicly-available-chest-x-ray-datasets-scientific-community)

This project was completed as part of the course [BMI 707](https://hms-dbmi.github.io/BMI_707/) in the Department of Biomedical Informatics at Harvard Medical School. A PDF of the report is embedded below, or access the [version on Google Drive](https://drive.google.com/file/d/1pGepJHb8YoOgiHD5lW3CseptOWil_zqO/view?usp=sharing/preview) directly. Here is a [link to the GitHub repository](https://github.com/mwestt/
BMI707-Project) hosting the code for the project.

---

<center>
<embed src="https://drive.google.com/file/d/1pGepJHb8YoOgiHD5lW3CseptOWil_zqO/preview" width="700" height="1000">
</center>

---
