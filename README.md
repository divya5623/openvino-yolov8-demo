# OpenVINO YOLOv8 Demo

This repository demonstrates conversion and optimization of YOLOv8 model using OpenVINO.

## Project Goals
- Convert YOLOv8 model to OpenVINO IR format
- Apply FP16 optimization
- Apply INT8 quantization
- Benchmark latency and throughput
- Compare baseline vs optimized performance
- Create reusable notebook for OpenVINO deployment

## Study Plan
- Understand OpenVINO model conversion workflow
- Learn YOLOv8 inference pipeline
- Implement OpenVINO runtime inference
- Apply optimization techniques (FP16, INT8)
- Benchmark CPU performance
- Visualize performance improvements

## Pipeline
1. Load pretrained YOLOv8 model
2. Convert model to OpenVINO IR
3. Apply FP16 optimization
4. Apply INT8 quantization
5. Run inference using OpenVINO runtime
6. Benchmark latency and throughput
7. Compare results

## Requirements
- Python 3.9+
- OpenVINO
- Ultralytics YOLOv8
- NumPy
- OpenCV

## Installation
pip install openvino ultralytics opencv-python numpy

## Expected Outcome
- Faster inference using OpenVINO
- Reduced model size
- Benchmark comparison
- Reusable deployment example

## Status
Work in progress (Created for GSoC 2026 proposal)
