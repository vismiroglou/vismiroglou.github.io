---
title: "Sea-ing Through Scattered Rays: Revisiting the Image Formation Model for Realistic Underwater Image Generation"
summary: "An improved underwater image formation model with forward scattering and a nonuniform medium, validated on the new BUCKET dataset."
date: 2026-02-23
tags: ["peer-reviewed", "conference"]

venue: "ICCV 2025 Workshops"

authorList:
  - name: Vasiliki Ismiroglou
  - name: Malte Pedersen
  - name: Stefan H. Bengtson
  - name: Andreas Aakerberg
  - name: Thomas B. Moeslund

links:
  - name: IEEE
    url: https://ieeexplore-ieee-org/abstract/document/10972542
    icon: file-lines
  - name: arXiv
    url: https://arxiv.org/abs/2509.15011
    icon: file-lines
  - name: Dataset
    url: https://huggingface.co/datasets/vapaau/THEBUCKETv1
    icon: download
  - name: Project page
    url: https://vap.aau.dk/sea-ing-through-scattered-rays/
    icon: globe

abstract: |
  In recent years, the underwater image formation model has found extensive use in the generation of synthetic underwater data. Although many approaches focus on scenes primarily affected by discoloration, they often overlook the model's ability to capture the complex, distance-dependent visibility loss present in highly turbid environments.

  In this work, we propose an improved synthetic data generation pipeline that includes the commonly omitted forward scattering term, while also considering a nonuniform medium. Additionally, we collected the **BUCKET** dataset under controlled turbidity conditions to acquire real turbid footage with the corresponding reference images. Our results demonstrate qualitative improvements over the reference model, particularly under increasing turbidity, with a selection rate of 82.5% by survey participants.
---
