---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-download-links">
  <a href="{{ base_path }}/files/cv.pdf" class="btn btn--primary">Download CV as PDF</a>
  <a href="{{ base_path }}" class="btn btn--inverse">View Markdown CV</a>
</div>

Education
======
### **Yonsei University**
Seoul, Korea / Mar.2020 - Feb.2027 (Expected)

B.S. Student in Physics<br>
B.S. Student in Electrical & Electronic Engineering

**Total GPA: 4.12/4.3**

Research Interests
======
Neural Network Compression, Diffusion Models, Physical AI

Undergraduate Projects (Selected)
======

### **100-class Face Recognition via Transfer Learning with Pre-trained ResNet-18**
Fall 2025, Introduction to Artificial Intelligence / Skills: Pytorch
- Implemented training pipelines for a given face recognition dataset (5,000 images, 100-class), considering its small size and low similarity to ImageNet
- Established a baseline by using linear probing and adjusting stem strides for resolution mismatch with ImageNet, achieving 56.4% accuracy.
- Improved the baseline by progressively expanding the fine-tuning scope with layer-wise learning rate decay and enhancing generalization through data augmentation tailored to model capacity.
- Achieved the highest accuracy **95.7%** by fine-tuning the entire network including stem layers, addressing the mismatch from the stride adjustment without training in the baseline.

### Training-free CAM-based Object Localization with Fully Convolutional ResNet-18
Fall 2025, Introduction to Artificial Intelligence / Skills: Pytorch
- Converted a pre-trained ResNet-18 into a fully convolutional network by replacing the GAP layer with average pooling and reformulating the FC layer as a $1\times1$ convolution.
- Performed object localization by upsampling class activation maps to the original input resolution and generating bounding boxes for regions exceeding a specific threshold.
- Analyzed model limitations, such as partial coverage of discriminative parts and the inability to localize multiple objects, unseen classes, or high-resolution images.

### Efficient CNN Accelerator Design using Row-stationary Dataflow and Ternary Quantization
Spring 2025, Intelligent System Design and Applications / Skills: Verilog, FPGA, PyTorch
- Applied the row-stationary dataflow to the line buffers to maximize data reuse and minimize redundant memory access during convolution.
- Reduced inference latency to 123.75 μs per image by utilizing the pooling layer as a buffer for pipelined layer execution and applying batch processing to alleviate BRAM-external memory bottlenecks.
- Enhanced inference efficiency by applying ternary quantization to INT8 weights, maintaining 95% accuracy through Leaky ReLU integration and hyperparameter optimization.

### Julia Set Visualization on FPGA with LCD Output
Fall 2024, Introductory Digital Labs / Skills: Verilog, FPGA
- Implemented an FSM-based system that computes the iterative formula of the Julia set using fixed-point multiplication (Q format).
- Developed an interactive Julia set visualizer on an LCD screen with adjustable parameters and zoom levels by mapping pixel coordinates to the complex plane.

Extracurricular Activities
======
### Yonsei Artificial Intelligence Club (YAI) 16th
Fall 2025 - Present
- Participated in group studies to discuss and review key computer vision papers (e.g., classification, object detection, generative models, etc.) and study the mathematical backgrounds (e.g., analysis)
- Implemented the reviewed models through collaborative projects using PyTorch.

### Diffusion Models Seminar (Instructor: Prof. Kyungwoo Song)
Dec. 2025 - Present
- Studied and discussed the theoretical foundations of diffusion models using ``The Principles of Diffusion Models" (Chieh-Hsin Lai et al.) as the primary textbook.
- Developed a unified and systemic perspective on diffusion models by interpreting Variational (VAE to DDPM), Score-based (EBM to NCSM), and Flow-based (NF to Flow matching) frameworks, including fast sampling and generation techniques.

Awards & Honors
======
- Honors (Feb. 2025)
- High Honors (Feb. 2021)
- Yonsei Veritas Scholarship (Jun. 2021, Feb. 2025, Aug. 2025)
GPA Based
- 2023 KMS Mathematics Competition for University Students (Dec. 2023)
Non-mathematics major fields, 3rd Prize
- 2020 Yonsei-Nexon $\sqrt{i}$ RC Creative Platform (Dec. 2020)
4th Prize

Skills
======
* Coding Skills: PyTorch, Python, Verilog HDL, C/C++, LaTeX

<!--
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
-->

Others
======
- Mandatory Military Service @ Republic of Korea Army (Nov. 2022 - May. 2024)
  <br>Sergeant, Honorable Discharge
