# MPEG-AI FCM Research

Undergraduate Research Project (2025-2026)
Korea Aerospace University

## Overview

Research on feature compression and restoration for MPEG-AI Feature Coding for Machines (FCM).

The objective was to improve compression efficiency while preserving downstream task performance without modifying the original bitstream structure.

## Contributions

### Resize Channel Pooling
- Replaced bilinear interpolation with adaptive average pooling
- Improved consistency for odd-sized feature maps
- Overall BD-rate improvement: -1.42%

### Active Channel Residual
- Replaced scalar mean restoration with pixel-wise residual restoration
- Used neighboring active channels for removed channel reconstruction
- Overall BD-rate improvement: -0.66%

## Experimental Environment

- MPEG-AI FCTM v10
- PyTorch

### Datasets
- SFU-HW (Object Detection)
- PANDAM (Semantic Segmentation)
- TVD / HIEVE (Object Tracking)

## Skills

PyTorch · Computer Vision · MPEG-AI · Feature Compression · Video Coding

## Documents

- Final Paper
- Presentation Slides
