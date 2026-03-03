# Adversarially Robust CNN for CIFAR-10

This notebook presents the implementation of a CNN for CIFAR-10 image classification with a dedicated focus on adversarial robustness. The model is evaluated under both standard and adversarial settings, including white-box (PGD) and black-box (PSO) attacks, to analyze performance degradation and robustness trade-offs.

NOTE:
All experiments were conducted in a CPU-only environment. Due to long training times, extensive experimentation with alternative optimization strategies and learning rate schedulers was computationally constrained. Expanded experimentation and fine-tuning will be performed once GPU resources are available.
