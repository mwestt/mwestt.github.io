---
title: "Simpsons Haiku Twitter Bot"
layout: post
date: 2022-10-07 12:43  
image: /assets/images/twitter-logo.png
headerImage: True
projects: True
tag:
- The Simpsons
- NLP
- Data Science
- Computational Poetry
- Cloud Computing
- Digital Art
star: true
category: project
author: Matthew West
description: A Twitter bot that tweets haiku derived from The Simpsons
mathjax: True
---

![png](/assets/images/47_ronin.png){: class="bigger-image"}


## [@SimpsonsHaiku](https://twitter.com/SimpsonsHaiku)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](https://github.com/mwestt/simpsons-haiku/blob/main/LICENSE)
[![Twitter](https://badgen.net/badge/icon/twitter?icon=twitter&label)](https://twitter.com/SimpsonsHaiku)

For anyone who knows me, they'll attest that The Simpsons has had an undue impact on my life, being formative through my early years and enduring to the present moment. That contribution spanned curating a sense of humour deeply anchored in an appreciation for the surreal, a continued love of animation, and exposure to the depths of obscure Americana (thank you, John Swartwzelder).

This project is the implementation of an idea I had long ago, inspired by [@nythaikus](https://twitter.com/nythaikus). Naturally, I'd been looking for an excuse to explore the world of The Simpsons via a data science project, and it finally came to fruition in the form of this Twitter bot. The dataset used here is hosted [on Kaggle here](https://www.kaggle.com/datasets/prashant111/the-simpsons-dataset), and was originally scraped by [Todd Schneider](https://toddwschneider.com/posts/the-simpsons-by-the-data/), covering the first 26 seasons. 

The GitHub repo for this project can be found [here](https://github.com/mwestt/simpsons-haiku). The bot itself is deployed via a GCP Cloud Function, and is running here, [@SimpsonsHaiku](https://twitter.com/SimpsonsHaiku). (Or at least it was, subject to auth issues since the API revamp, thanks Elon).



<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Or the dogs with bees<br>in their mouths and when they bark<br>they shoot bees at you</p>&mdash; Simpsons Haiku Bot (@SimpsonsHaiku) <a href="https://twitter.com/SimpsonsHaiku/status/1612056551015043074?ref_src=twsrc%5Etfw">January 8, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>