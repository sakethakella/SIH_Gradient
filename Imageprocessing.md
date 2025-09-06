# Embedded Deep Learning Image Processing: Software Overview

Embedded deep learning enables advanced image processing directly on resource-constrained devices such as microcontrollers, FPGAs, and edge AI hardware. This approach is crucial for real-time applications in robotics, IoT, automotive, and smart cameras.

## Key Software Components

### 1. Frameworks & Libraries

- **TensorFlow Lite**  
   Optimized for mobile and embedded devices. Supports quantization and hardware acceleration.

- **ONNX Runtime**  
   Cross-platform inference engine supporting multiple hardware backends.

- **PyTorch Mobile**  
   Lightweight version of PyTorch for mobile and edge deployment.

- **OpenCV**  
   Widely used for image processing; integrates with deep learning models.

- **Arm NN**  
   Neural network inference engine for Arm Cortex CPUs, Mali GPUs, and Ethos NPUs.

### 2. Model Optimization Tools

- **TensorFlow Model Optimization Toolkit**  
   Pruning, quantization, and clustering for efficient models.

- **NVIDIA TensorRT**  
   High-performance deep learning inference optimizer for NVIDIA GPUs.

- **Edge TPU Compiler**  
   Compiles models for Google Coral Edge TPU devices.

### 3. Deployment Platforms

- **Raspberry Pi**  
   Popular for prototyping; supports TensorFlow Lite, OpenCV, and PyTorch.

- **NVIDIA Jetson**  
   Powerful edge AI platform with GPU acceleration.

- **Google Coral**  
   Edge TPU hardware for fast, low-power inference.

- **STM32 Microcontrollers**  
   Supports CMSIS-NN and Arm NN for efficient inference.

## Typical Workflow

1. **Model Training:** Train on desktop/server using TensorFlow, PyTorch, etc.
2. **Model Optimization:** Apply quantization/pruning for embedded deployment.
3. **Conversion:** Convert model to suitable format (e.g., TFLite, ONNX).
4. **Deployment:** Load and run model on embedded device using supported runtime.
5. **Integration:** Combine with image acquisition and preprocessing pipelines.

## References

- [TensorFlow Lite](https://www.tensorflow.org/lite)
- [ONNX Runtime](https://onnxruntime.ai/)
- [PyTorch Mobile](https://pytorch.org/mobile/home/)
- [OpenCV](https://opencv.org/)
- [NVIDIA Jetson](https://developer.nvidia.com/embedded-computing)
