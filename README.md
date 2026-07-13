# sHū addi Smart Inventory Counter

## Team Members

- Eric Jon Smith II

---

## Project Tier

Tier 1 (Core)

This project uses a single YOLOv8 object detection model to detect and count apparel items for inventory management.

---

## Problem Statement

Small apparel businesses spend valuable time manually counting inventory before events, restocking, and fulfilling customer orders. Manual counting can lead to errors, inaccurate inventory records, and wasted time.

---

## Solution Overview

The system will analyze an image of apparel products using computer vision. It will detect hats, shirts, and socks, count each item, and generate an inventory report.

---

## Technical Approach

**CV Technique**
- Object Detection

**Model Architecture**
- CNN

**Model**
- YOLOv8n

**Framework**
- Ultralytics YOLO with PyTorch

**How it will be used**
- Pretrained model with optional transfer learning.

---

## Dataset

**Source**
- Roboflow Universe
- Self-collected sHū addi product images

**Estimated Size**
- 300–500 images

**Labels**
- Hats
- Shirts
- Socks

---

## Success Metrics

**Primary**
- Detection accuracy of at least 90%

**Secondary**
- Inventory counting accuracy of at least 95%
- Processing time under one second per image

---

## Milestone Plan

| Phase | Timeline |
|--------|----------|
| Blueprint | Week 5 |
| First Working Demo | Week 6 |
| Make It Yours | Weeks 7–8 |
| Improve & Measure | Week 9 |
| Final Build | Week 10 |

---

## Resources

- Google Colab
- Ultralytics YOLO
- PyTorch
- Roboflow Universe

Cost: $0

---

## Risks

**Risk 1**
Limited training images.

**Plan B**
Use public Roboflow datasets.

**Risk 2**
Poor detection due to lighting.

**Plan B**
Collect additional photos under different lighting conditions.

---

## AI Usage Log

Located in:

docs/AI_usage_log.md
