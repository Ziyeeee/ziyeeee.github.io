---
title:          "GauDP: Reinventing Multi-Agent Collaboration through Gaussian-Image Synergy in Diffusion Policies "
date:           2025-09-19 00:00:00 +0800
selected:       true
pub:            "The Thirty-ninth Annual Conference on Neural Information Processing Systems (NeurIPS)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-primary">Poster</span>'
pub_date:       "2025"

abstract: >-
    Recently, effective coordination in embodied multi-agent systems remains a fundamental challenge—particularly 
    in scenarios where agents must balance individual perspectives with global environmental awareness. Existing 
    approaches often struggle to balance fine-grained local control with comprehensive scene understanding, resulting 
    in limited scalability and compromised collaboration quality.

    In this paper, we present <strong>GauDP</strong>, a novel Gaussian-image synergistic representation that facilitates 
    scalable, perception-aware imitation learning in multi-agent collaborative systems.
    Specifically, <strong>GauDP</strong> constructs a globally consistent 3D Gaussian field from decentralized RGB 
    observations, then dynamically redistributes 3D Gaussian attributes to each agent's local perspective. This enables 
    all agents to adaptively query task-critical features from the shared scene representation while maintaining their 
    individual viewpoints.
    This design facilitates both fine-grained control and globally coherent behavior without requiring additional 
    sensing modalities (e.g., 3D point cloud). 

    We evaluate <strong>GauDP</strong> on the RoboFactory benchmark, which includes diverse multi-arm manipulation tasks. 
    Our method achieves superior performance over existing image-based methods and approaches the effectiveness of 
    point-cloud-driven methods, while maintaining strong scalability as the number of agents increases.
cover:          /assets/images/covers/cover_neurips2025.png
authors:
  - Ziye Wang*
  - Li Kang*
  - Yiran Qin 
  - Jiahua Ma
  - Zhanglin Peng
  - Lei Bai
  - Ruimao Zhang#
links:
  Paper: https://arxiv.org/pdf/2511.00998
  Code: https://github.com/Ziyeeee/Policy-Lightning
  Project Page: https://ziyeeee.github.io/gaudp.io
---
