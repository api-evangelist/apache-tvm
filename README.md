# Apache TVM (apache-tvm)
Apache TVM is an open-source compiler framework for deep learning that provides performance portability across CPUs, GPUs, FPGAs, and specialized accelerators. It automatically optimizes models from TensorFlow, PyTorch, ONNX, and other frameworks for edge and cloud deployment.

**URL:** [https://tvm.apache.org/](https://tvm.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AI, Compiler, Deep Learning, Edge Computing, Model Optimization, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache TVM Python API
Comprehensive Python interface for model compilation, optimization, and deployment including tvm.relay, tvm.auto_scheduler, tvm.micro, and tvm.rpc modules.

**Human URL:** [https://tvm.apache.org/docs/reference/api/python/](https://tvm.apache.org/docs/reference/api/python/)

#### Tags:

 - Python, Deep Learning, Model Optimization, Compiler

#### Properties

- [Documentation](https://tvm.apache.org/docs/reference/api/python/)
- [Python Package (PyPI)](https://pypi.org/project/apache-tvm/)

### Apache TVM RPC API
Remote compilation, deployment, and profiling of optimized models on target devices for AutoTVM/AutoScheduler tuning jobs.

**Human URL:** [https://tvm.apache.org/docs/how_to/work_with_microtvm/](https://tvm.apache.org/docs/how_to/work_with_microtvm/)

#### Tags:

 - RPC, Remote, Profiling, Hardware

#### Properties

- [Documentation](https://tvm.apache.org/docs/how_to/work_with_microtvm/)

## Common Properties

- [GitHubRepository](https://github.com/apache/tvm)
- [Documentation](https://tvm.apache.org/docs/)
- [Portal](https://tvm.apache.org/)
- [GettingStarted](https://tvm.apache.org/docs/get_started/)
- [ReleaseNotes](https://github.com/apache/tvm/releases)
- [Support](https://discuss.tvm.apache.org/)
- [TermsOfService](https://www.apache.org/licenses/)

## Features

| Name | Description |
|------|-------------|
| Multi-Framework Support | Import models from TensorFlow, PyTorch, ONNX, MXNet, Keras, and other frameworks. |
| Hardware-Specific Optimization | Automatic operator scheduling and kernel fusion for CPUs, GPUs, and accelerators. |
| Auto-Tuning | AutoTVM and AutoScheduler for automated compute kernel hyperparameter optimization. |
| MicroTVM | Deploy optimized models on microcontrollers and bare-metal devices. |
| BYOC Framework | Bring Your Own Codegen for integrating custom hardware accelerators. |
| Relay IR | High-level intermediate representation for end-to-end model optimization. |

## Use Cases

| Name | Description |
|------|-------------|
| Edge AI Deployment | Deploy optimized deep learning models on edge devices and microcontrollers. |
| Model Serving Optimization | Optimize inference performance for cloud GPU/CPU model serving. |
| Cross-Platform Deployment | Compile a single model for multiple hardware targets. |
| Custom Accelerator Integration | Integrate custom AI accelerators using TVM's BYOC framework. |

## Integrations

| Name | Description |
|------|-------------|
| ONNX | Import and optimize ONNX models from any ONNX-compatible ML framework. |
| PyTorch | TorchScript to TVM compilation for PyTorch model optimization. |
| TensorFlow | TensorFlow and TFLite model import and optimization. |
| NVIDIA CUDA | CUDA/cuDNN backend for NVIDIA GPU kernel generation and optimization. |
| ARM | ARM CPU (Cortex-A, Cortex-M) and ARM Mali GPU backend support. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
