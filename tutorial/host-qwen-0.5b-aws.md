# Host Qwen 0.5B on AWS

We want to setup minium cost Qwen modal on AWS.

## Why is Qwen 0.5B?

Qwen 0.5B is one of the smallest modal in the market maintain by one of the top tech companies, Alibaba.

## Setup

## FAQ

1. Nvida TensorRT vs ONNX, which one is better?

It depends on the requirement, TensorRT is more native to Nvidia ecosystem, with better support on using 
GPU, and ONNX could support both GPU and CPU. In our example, we want to have lowest cost setup, ONNX 
would be a better option.

