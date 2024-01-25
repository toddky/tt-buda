# TT-BUDA

## Table of Contents

- [Introduction](#introduction)
- [First 5 Things To-Do](#first-5-things-to-do)
- [Model Demos](#model-demos)
- [Documentation](#documentation)
- [FAQ & Troubleshooting](#faq--troubleshooting)
- [Communication](#communication)

## Introduction

The TT-BUDA software stack can compile AI/ML models from several different frameworks such as PyTorch and Tensorflow, and execute them in many different ways on Tenstorrent hardware.

**Note on terminology:**

TT-BUDA is the official Tenstorrent AI/ML compiler stack and PyBUDA is the Python interface for TT-BUDA. PyBUDA allows users to access and utilize TT-BUDA's features directly from Python. This includes directly importing model architectures and weights from PyTorch, TensorFlow, ONNX, and TFLite.

## First 5 Things To-Do

1. [Install TT-Buda](first_5_steps/1_install_tt_buda.md) -> Installation guide
1. [Run NLP models](first_5_steps/2_running_nlp_models.ipynb) -> Run your first NLP model
1. [Run CNN models](first_5_steps/3_running_cv_models.ipynb) -> Run your first CNN model with TT-BUDA
1. [Batched inputs](first_5_steps/4_batched_inputs.ipynb) -> Learn how to run with batched inputs and how to benchmark models
1. [Serving TT models](first_5_steps/5_serving_tt_models.ipynb) -> Use FastAPI to host a model running on Tenstorrent hardware to build custom APIs

## Model Demos

For additional example code for running some popular AI/ML models, please visit [model_demos](model_demos/).

## Documentation

Please refer to the [official documentation website](https://docs.tenstorrent.com/tenstorrent/).

## FAQ & Troubleshooting

We keep a running FAQ & troubleshoot guide to help you quickly resolve some of the most common issues at [FAQ & Troubleshooting](FAQ.md).

## Communication

If you would like to formally propose a new feature, report a bug, or have issues with permissions, please file through [GitHub issues](https://github.com/tenstorrent/tt-buda/issues).

Please access the [Discord community](https://discord.gg/xUHw4tMcRV) forum for updates, tips, live troubleshooting support, and more!
