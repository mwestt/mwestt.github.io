---
title: "Machine Learning for Healthcare: Transfer Learning for Cancer Classification"
layout: post
date: 2020-03-17 18:32
image: /assets/images/MIT_logo.svg
headerImage: True
projects: true
tag:
- Cancer Classification
- Deep Learning
- Machine Learning
star: true
category: project
author: Matthew West
description: Research Project for MIT 6.862
mathjax: True
---

This is the project page for my research project undertaken for the course MIT 6.862, [Applied Machine Learning.](http://student.mit.edu/catalog/m6c.html#6.862)

In this project, I decided to investigate the application of deep learning to breast cancer images, showing that transfer learning improved cancer classification on a small dataset, using ImageNet weights.

This dataset was the corresponding raw image data to the [Wisconsin Breast Cancer dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)), which was generously made available by [Professor Nick Street](https://tippie.uiowa.edu/people/nick-street) at the University of Iowa.

As this dataset is very small, this improvement in classification performance demonstrates that ImageNet weights and architectures can provide useful features for classification problems on data that differ significantly from ImageNet data. Despite working well for such a small dataset, this does not appear to be the case for medical imaging in general, and it is evident that transfer learning applications in medical imaging would benefit greatly from having their own benchmark dataset. This idea and several others are explored in detail by [Maithra Raghu](https://twitter.com/maithra_raghu?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor) et al. in [this conference paper](https://arxiv.org/abs/1902.07208) from NeurIPS 2019. 

The PDF of the report is embedded below, or access the [version on google drive](https://drive.google.com/open?id=1dxnx8sTwUeU7kLTjMS-kvfIhBtRyebS6) directly. Here is a [link to the GitHub repository](https://github.com/mwestt/MIT-6.862) for associated files relevant to the project.


---

<center>
<embed src="https://drive.google.com/file/d/1dxnx8sTwUeU7kLTjMS-kvfIhBtRyebS6/preview" width="500" height="375">
</center>

---
