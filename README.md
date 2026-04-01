CTFSL: Cross-Task Few-Shot Learning with Structural Alignment for Hyperspectral Image Change Detection
Under limited labeled samples, hyperspectral image change detection (HSI-CD) remains challenging due to insufficient semantic supervision and sensitivity to subtle spectral variations. Existing few-shot approaches alleviate data scarcity but rely on binary labels, resulting in representations that lack fine-grained semantic structure.

To address these issues, we propose a Cross-Task Few-Shot Learning framework (CTFSL) that transfers semantic knowledge from hyperspectral classification to change detection. This project includes the following core contributions:

Task-Level Structural Alignment (TLSA) mechanism: Mitigates the discrepancy between multi-class and binary supervision, enabling the learning of task-compatible representations.

Collaborative Adaptation (CDA) strategy: Aligns feature distributions while preserving discriminative structure, enhancing robustness under domain shift.

Frequency-aware Multi-scale Feature Extractor (FMFE): Explicitly models spectral-spatial variations across different frequency components, improving sensitivity to subtle changes.

(Requirements)

Please ensure your running environment meets the following conditions:

Python >= 3.8

PyTorch >= 1.10.0
