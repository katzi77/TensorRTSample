# TensortRT sample

Sample code for running inference on resnet-50 produced with PyTorch
based on https://www.learnopencv.com/how-to-run-inference-using-tensorrt-c-api/
,inlcudes fixes for switching from TensorRT-6 to TensorRT-7

## Requirements
- TensorRT-7.2.1.6
- cudnn-10.2-windows10-x64-v8.0.5.39
- OpenCV 4.1.1 compiled with CUDA support

## Status
This code is work in progress.

## Known issues
When running with batch size > 1, inference results for batch indices > 0 are wrong, and inference for indice 0 is fine.
