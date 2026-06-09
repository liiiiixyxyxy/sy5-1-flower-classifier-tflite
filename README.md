# 花卉图片分类器：Keras 训练并导出 TFLite

本教程使用 TensorFlow/Keras 训练花卉图片分类模型，并转换为 TensorFlow Lite 的 `.tflite` 文件，不依赖 `tflite-model-maker`，彻底解决版本冲突问题。

## 环境要求

- Python 3.10 / 3.11+
- TensorFlow >= 2.15
- Matplotlib >= 3.7
- NumPy >= 1.23

## 快速开始

### 1. 安装依赖

```bash
pip install tensorflow>=2.15 matplotlib>=3.7 numpy>=1.23
