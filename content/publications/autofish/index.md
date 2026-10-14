---
title: "AutoFish: Dataset and Benchmark for Fine-grained Analysis of Fish"
summary: "A new dataset and metric for measuring how turbidity degrades computer-vision performance underwater."
date: 2025-04-29
tags: ["peer-reviewed", "conference"]

authorList:
  - name: Stefan Hein Bengtson
  - name: Daniel Lehotský
  - name: Vasiliki Ismiroglou
  - name: Niels Madsen
  - name: Thomas B. Moeslund
  - name: Malte Pedersen

links:
  - name: Paper (IEEE)
    url: https://ieeexplore.ieee.org/abstract/document/10972542
    icon: file-lines
  - name: arXiv
    url: https://arxiv.org/abs/2501.03767
    icon: file-lines
  - name: Dataset
    url: https://huggingface.co/datasets/vapaau/autofish
    icon: download
  - name: Project page
    url: https://vap.aau.dk/autofish/
    icon: globe

abstract: |
  Automated fish documentation processes are in the near future expected to play an essential role in sustainable fisheries management and for addressing challenges of overfishing. In this paper, we present a novel and publicly available dataset named AutoFish designed for fine-grained fish analysis. The dataset comprises 1,500 images of 454 specimens of visually similar fish placed in various constellations on a white conveyor belt and annotated with instance segmentation masks, IDs, and length measurements. The data was collected in a controlled environment using an RGB camera. The annotation procedure involved manual point annotations, initial segmentation masks proposed by the Segment Anything Model (SAM), and subsequent manual correction of the masks. We establish baseline instance segmentation results using two variations of the Mask2Former architecture, with the best performing model reaching an mAP of 89.15%. Additionally, we present two baseline length estimation methods, the best performing being a custom MobileNetV2-based regression model reaching an MAE of 0.62cm in images with no occlusion and 1.38cm in images with occlusion.
---
