Edge AI for Pest Detection in Tomato Plants

Bachelor's thesis — Data Science & AI, Maastricht University

Real-time pest detection system for tomato plants, designed to run directly on resource-constrained microcontrollers (MCUs) rather than relying on cloud inference — critical for deployment in greenhouse/field environments with limited connectivity.

Approach
Object detection: YOLOv5 and YOLOv8 architectures trained for pest identification
Model compression: Structured pruning to reduce network size while preserving accuracy
Quantization: INT8 quantization for efficient on-device inference on MCU-class hardware
Target: Low-latency, low-power detection suitable for edge deployment in agricultural settings
Why it matters

Traditional pest detection relies on manual inspection or cloud-based inference, which doesn't scale well for continuous greenhouse monitoring. This work demonstrates that accurate detection is achievable directly on cheap embedded hardware, cutting latency and removing the dependency on connectivity.
