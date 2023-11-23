---
title: Introduction
permalink: /docs/Introduction/
---

Introduce your project here. The following is an example.


<img src="https://i.ibb.co/54vTYzk/ssl-logo.png" alt="ssl-logo" border="0">

<p float="left">
    <img src="https://img.shields.io/badge/python-v3.7+-red" alt="Python 3.7+ Badge">
    <img src="https://img.shields.io/badge/pytorch-v1.7+-blue" alt="PyTorch 1.7+ Badge">
    <img src="https://img.shields.io/badge/tensorflow-v1.14+-green" alt="TensorFlow 1.14+ Badge"><br>
</p>

**SELFRec** is a Python framework for self-supervised recommendation (SSR) which integrates commonly used datasets and metrics, and implements many state-of-the-art SSR models. SELFRec has a lightweight architecture and provides user-friendly interfaces. It can facilitate model implementation and evaluation.<br>
**Founder and principal contributor**: [@Coder-Yu](https://github.com/Coder-Yu) [@xiaxin1998](https://github.com/xiaxin1998) <br>
**Supported by**: [@AIhongzhi](https://github.com/AIhongzhi) ([A/Prof. Hongzhi Yin](https://sites.google.com/view/hongzhi-yin/home), UQ)

This repo is released with our [survey paper](https://arxiv.org/abs/2203.15876) on self-supervised learning for recommender systems. We organized a tutorial on self-supervised recommendation at WWW'22. Visit the [tutorial page](https://ssl-recsys.github.io/) for more information.

<h2>Architecture</h2>
<img src="https://raw.githubusercontent.com/Coder-Yu/SELFRec/main/selfrec.jpg" alt="SELFRec Architecture" border="0" style="width:600px">

<h2>Features</h2>
<ul>
    <li><b>Fast execution</b>: SELFRec is compatible with Python 3.8+, Tensorflow 1.14+, and PyTorch 1.8+ and powered by GPUs. We also optimize the time-consuming item ranking procedure, drastically reducing ranking time to seconds.</li>
    <li><b>Easy configuration</b>: SELFRec provides simple and high-level interfaces, making it easy to add new SSR models in a plug-and-play fashion.</li>
    <li><b>Highly Modularized</b>: SELFRec is divided into multiple discrete and independent modules. This design decouples model design from other procedures, allowing users to focus on the logic of their method and streamlining development.</li>
    <li><b>SSR-Specific</b>: SELFRec is designed specifically for SSR. It provides specific modules and interfaces for rapid development of data augmentation and self-supervised tasks.</li>
</ul>

<h2>Requirements</h2>

```
numba==0.53.1
numpy==1.20.3
scipy==1.6.2
tensorflow==1.14.0
torch>=1.7.0
```

<h2>Usage</h2>
<ol>
    <li>Configure the xx.conf file in the directory named conf. (xx is the name of the model you want to run)</li>
    <li>Run main.py and choose the model you want to run.</li>
</ol>

<h2>Implemented Models</h2>

<table class="table table-hover table-bordered">
  <tr>
		<th>Model</th> 		<th>Paper</th>      <th>Type</th>   <th>Code</th>
   </tr>
   <!-- Add rows for each model -->
   <!-- Example row -->
   <tr>
    <td scope="row">SASRec</td>
        <td>Kang et al. <a href="https://cseweb.ucsd.edu/~jmcauley/pdfs/icdm18.pdf" target="_blank">Self-Attentive Sequential Recommendation</a>, ICDM'18.
         </td> <td>Sequential</td> <td>PyTorch</td> 
      </tr>
   <!-- More rows following the same pattern -->
</table>

<!-- Repeat the table structure for additional models -->

<h2>Leaderboard</h2>
<!-- Leaderboard Table -->

<h2>Implement Your Model</h2>
<!-- Instructions for implementing new models -->

<h2>Related Datasets</h2>
<!-- Table of related datasets -->

<h2>Reference</h2>

```
@article{yu2023self,
  title={Self-supervised learning for recommender systems: A survey},
  author={Yu, Junliang and Yin, Hongzhi and Xia, Xin and Chen, Tong and Li, Jundong and Huang, Zi},
  journal={IEEE Transactions on Knowledge and Data Engineering},
  year={2023},
  publisher={IEEE}
}
```

