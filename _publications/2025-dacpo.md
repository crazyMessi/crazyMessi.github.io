---
title: "A Divide-and-Conquer Approach for Global Orientation of Non-Watertight Scene-Level Point Clouds Using 0-1 Integer Optimization"
collection: publications
category: manuscripts
permalink: /publication/2025-dacpo
excerpt: 'A novel framework for orienting large-scale scene point clouds using divide-and-conquer strategy and Boolean programming.'
date: 2025-07-01
venue: 'ACM Transactions on Graphics'
paperurl: 'https://doi.org/10.1145/3730923'
citation: 'Li, Zhuodong, Fei Hou, Wencheng Wang, Xuequan Lu, and Ying He. "A Divide-and-Conquer Approach for Global Orientation of Non-Watertight Scene-Level Point Clouds Using 0-1 Integer Optimization." ACM Trans. Graph. 44.4 (2025).'
---

<div style="display: flex; align-items: flex-start; margin-bottom: 30px;">
  <div style="flex-shrink: 0; margin-right: 20px;">
    <img src="../images/dacpo_teaser.jpg" alt="DACPO Teaser" style="width: 120px; height: auto; border: 1px solid #ddd;">
  </div>
  <div>
    <h3 style="color: #D2691E; margin-top: 0; margin-bottom: 8px; font-size: 18px;">A Divide-and-Conquer Approach for Global Orientation of Non-Watertight Scene-Level Point Clouds Using 0-1 Integer Optimization</h3>
    <p style="margin: 5px 0; font-style: italic;"><strong>Zhuodong Li</strong>, Fei Hou, Wencheng Wang, Xuequan Lu, Ying He</p>
    <p style="margin: 5px 0; font-weight: bold;">ACM Transactions on Graphics 2025</p>
    <p style="margin: 10px 0;">
      <a href="https://doi.org/10.1145/3730923" style="margin-right: 10px;">[Paper]</a>
      <a href="https://arxiv.org/abs/2505.23469" style="margin-right: 10px;">[arXiv]</a>
      <a href="https://github.com/zd-lee/DACPO" style="margin-right: 10px;">[Code]</a>
    </p>
  </div>
</div>

## Abstract

We propose a divide-and-conquer framework for orienting large-scale scene point clouds. Our method partitions the input cloud into patches and refines normals within each patch using propagation and iterative Poisson reconstruction. We formulate a Boolean programming model based on the principle of visible surface consistency to achieve global orientation consistency. Our approach achieves significant accuracy improvements over state-of-the-art methods under varying sparsity and noise levels on ScanNet and SceneNN datasets.