---
title: "Bridging Data-Rich and Data-Poor Domains in Lithium-Ion Batteries Using SEM Data via CNN Transfer Learning"
collection: publications
category: additional
permalink: /publication/2025-neurips-battery-transfer
date: 2025-12-01
venue: 'AI for Accelerated Materials Discovery Workshop (AI4Mat), NeurIPS 2025'
paperurl: 'https://openreview.net/pdf?id=j3aOU8Ahue'
authors: "Haein Jeon, Donghun Lee, Bo-Yeong Kang, and Jimin Oh"
abstract: "Scanning Electron Microscopy (SEM) imaging provides a powerful yet often underutilized method for diagnosing the state of lithium-ion battery cathodes. However, deep learning models for SEM-based state prediction often struggle with limited training data and domain shifts, especially when functional electrolyte additives are added. In this work, we propose a two-stage transfer learning framework using an EfficientNet-B0 backbone to robustly classify cathode SEM images across nine classes defined by material composition (NCM333, NCM622, NCM811) and aging state (pristine, formation-aged, 100 cycles). Our method first pretrains the model on a data-rich source domain of additive-free samples, then fine-tunes it on a smaller target domain containing additive-induced variations. To address class imbalance, we compare targeted oversampling and weighted loss strategies. Experimental results show that our framework consistently outperforms pretrainingonly and fine-tuning-only baselines, achieving over 0.98 accuracy and F1 scores for domain-shifted classes. Qualitative analysis with Grad-CAM shows that the model identifies important physical features, such as particle cracking and boundary degradation. These findings demonstrate the effectiveness of transfer learning in reducing data scarcity and domain shift in SEM-based battery diagnostics, providing a practical solution for automated analysis in the development of next-generation batteries."
---
