---
title: "Beyond Aesthetics: Quantifying Information Loss in Turbid Scenes"
date: 2026-09-25
tags: ["peer-reviewed", "conference"]

authorList:
  - name: Vasiliki Ismiroglou
  - name: Stefan H. Bengtson
  - name: Tasos Benos
  - name: Thomas B. Moeslund
  - name: Malte Pedersen

links:
  - name: arXiv
    url: https://arxiv.org/abs/2606.26295
    icon: file-lines

abstract: |
  Visibility in underwater environments degrades rapidly under turbid conditions, yet the effects on computer-vision models remain unclear. This issue is compounded by reliance on synthetic turbidity datasets, which may misrepresent real-world information loss.

  To address this gap, we introduce the **Turbid Underwater Baseline (TUB)** dataset, comprising 1,320 images captured under extreme turbidity and over 16,000 high-confidence ground-truth segmentation masks. We additionally propose **PCD**, a metric derived from phase congruency maps that is invariant to contrast and aims to capture the loss of structural information in real turbidity. We show that PCD correlates strongly with the performance of instance segmentation models on both real and synthetic turbid images, whereas common metrics in the field show weak to no correlation at all.
---
