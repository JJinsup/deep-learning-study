# tf-learning
🔱 Terraforming with TensorFlow: A study archive on the Server (AMD EPYC + CUDA 12.9).

# 🧠 tf-learning

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=flat-square&logo=python&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-22.04-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-12.9-76B900?style=flat-square&logo=nvidia&logoColor=white)

**TensorFlow 2.x Learning Roadmap** based on official documentation.
이 레포지토리는 [TensorFlow 공식 튜토리얼](https://www.tensorflow.org/tutorials?hl=ko)과 [가이드](https://www.tensorflow.org/guide?hl=ko)를 실습하고 정리한 아카이브입니다.

<br>

## 🖥️ Environment: Server 🔱

| Hardware | Specs |
| :--- | :--- |
| **CPU** | AMD EPYC 7713 (64-Core Processor) |
| **RAM** | 503 GB |
| **GPU** | RTX 3090 (Current Driver: 575.64) |
| **OS** | Ubuntu 22.04.5 LTS |

> **Note:** `conda` 가상환경(`tutorial`)에서 `pip install "tensorflow[and-cuda]"`로 환경을 구축했습니다.

<br>

## 📂 Directory Structure

```bash
tf-learning/
├── 00_Environments/     # 환경 설정 및 GPU 테스트 코드
├── 01_Beginner/         # 초보자용 튜토리얼 (Keras)
├── 02_Advanced/         # 전문가용 튜토리얼 (GradientTape 등)
├── 03_Guide/            # TF 가이드 (Tensor, Variable, Autodiff)
└── README.md
```

<br>

## 📝 Study Log

| Date | Chapter | Topic | Status |
| :---: | :--- | :--- | :---: |
| 2025.11.22 | Env Setup | Conda 환경 구축 및 GitHub 연동 | ✅ |
| 2025.11.23 | Basic | 텐서(Tensor)와 연산 | 🏃 |
| ... | ... | ... | 🔒 |

<br>

---
_Powered by TensorFlow 2.16+
