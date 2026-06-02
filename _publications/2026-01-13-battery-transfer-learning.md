---
title: "Transfer Learning Framework for SEM-Based Degraded Lithium-ion Battery Diagnostics under Domain Shift and Data Scarcity"
collection: publications
category: additional
permalink: /publication/2026-battery-transfer-learning
date: 2026-01-13
venue: 'Journal of Power Sources (in revision)'
authors: "Haein Jeon, Donghun Lee, Bo-Yeong Kang, and Jimin Oh"
paperurl: ''
abstract: 'Scanning Electron Microscopy (SEM) imaging provides a powerful yet often underutilized method for diagnosing the state of lithium-ion battery cathodes. However, deep learning models for SEM-based state prediction often struggle with limited training data and domain shifts, especially when rare functional electrolyte additive data are added. In this work, we propose a two-stage transfer learning framework using an EfficientNet-B0 backbone to robustly classify cathode SEM images across nine classes defined by material composition (NCM333, NCM622, NCM811) and degradation state (pristine, formation-aged, 100 cycles). For practical application, our method first pretrains the model on a data-rich source domain of additive-free samples, then fine-tunes it on a smaller target domain containing additive-induced variations. To address class imbalance, we compare targeted oversampling and weighted loss strategies. Experimental results show that our framework consistently outperforms pretraining-only and fine-tuning-only baselines, achieving a macro-averaged F1 of 0.980 (±0.043) across 10 independent runs. Grad-CAM visualizations suggest that the model attends to morphologically relevant regions such as particle cracking and boundary degradation, supporting the physical interpretability of the learned representations. These findings demonstrate the effectiveness of transfer learning in reducing data scarcity and domain shift in SEM-based battery diagnostics, providing a practical solution for automated analysis in the development of next-generation batteries. '
---
