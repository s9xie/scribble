---
layout: post_project_page
title: Deeply Supervised Nets
date: 2014-09-12 11:49:31
disqus: n
share: y
---

<p style="text-align:center"><img src="{{site.baseurl}}/images/dsn/architecture.png" alt="Drawing" align="center" style="width: 650px;"/></p>
<p style="text-align:center">Fig1: Deeply-supervised Nets architecture and cost functions illustration</p>

Abstract
-----
Our proposed deeply-supervised nets (DSN) method simultaneously minimizes classification error while making the learning process of hidden layers direct and transparent. We make an attempt to boost the classification performance by studying a new formulation in deep networks. Three aspects in deep learning (supervised) style architectures are being looked at: (1) transparency of the intermediate layers to the overall classification; (2) effectiveness in training due to the presence of the exploding and vanishing gradients; (3) discriminativity of learned features, especially in the early layers. We introduce “companion loss” to the individual hidden layers, in addition to the overall loss at the output layer (a different strategy to layer-wise pre-training). We use techniques from stochastic gradient methods to analyze our algorithm. The advantage of our method is evident and our experimental result on various benchmark datasets shows significant performance boost (e.g. all state-of-the-art results on MNIST, CIFAR-10, CIFAR-100, and SVHN).

---

Experiments
---
Our results on several benchmark datasets are listed below:

<p style="text-align:center"><img src="{{site.baseurl}}/images/dsn/results.png" alt="Drawing" aligh="center" style="width: 600px;"/></p>
<p style="text-align:center">Fig2: Test accuracy on different benchmark datasets. </p>

<p style="text-align:center"><img src="{{site.baseurl}}/images/dsn/visualization4.png" alt="Drawing" aligh="center" style="width: 600px;"/></p>
<p style="text-align:center">Fig3: Visualization of the convolutional feature map learned by DSN</p>

**Update:** With a little bit further tuning (basically training more epochs). We updated our results on CIFAR-10 with **9.69%** and **7.97%** (w\ and w\o data augmentation), both using a single model.

Code, preprocessed data and configuration files will become available.

<a href="https://github.com/s9xie/DSN" target="_blank" class="big-button gray">Get it on GitHub</a>

---

Publication
---
**[1] Deeply-Supervised Nets [\[pdf\]](/)** <br> Chen-Yu Lee\*, Saining Xie\*, Patrick Gallagher, Zhengyou Zhang and Zhuowen Tu (* indicates equal contributions)<br> **arXiv:1312.xxxx**, Sept 2014, originally submitted to NIPS 2014

---

Disclosure
---
**Deeply-supervised neural networks**, Zhuowen Tu, Chen-Yu Lee, and Saining Xie<br>UCSD Docket No. SD2014-313, May 22, 2014

---
<!--Special thanks to [Min Lin](http://github.com/mavenlin) and [Naiyan Wang](http://winsty.net) for encouraging discussions and help.-->

Like it? [Tell me](mailto:xiesaining@gmail.com).<br/>
Problem? [Use GitHub Issues](https://github.com/s9xie/DSN).
