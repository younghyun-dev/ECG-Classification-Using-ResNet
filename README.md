# ECG Multi-Class Classification Challenge

ECG 데이터를 활용하여 심장 질환을 분류하는 AI 모델 개발 프로젝트입니다.

## Project Overview

- 기간 : 2024.09 ~ 2024.12
- 인원 : 3명

### 담당 역할
- ResNet 모델 구현
- ECG 데이터 전처리
- Low-pass Filter(IIR, FIR) 적용
- 하이퍼파라미터 튜닝
- 모델 성능 평가

## Tech Stack

- Python
- PyTorch
- NumPy
- SciPy
- Scikit-learn
- Google Colab

## Performance

- Weighted F1-score : 99.31%

## Architecture

![Architecture](images/architecture.png)

## Result

![Result](images/result.png)

## Troubleshooting

### 1. Model Improvement

SimpleCNN → ResNet18 → ResNet34 순으로 모델 구조를 개선하며 성능을 비교하였습니다.

![Model](images/troubleshooting_model.png)

### 2. Low-pass Filter

ECG 신호의 고주파 노이즈 제거를 위해 IIR/FIR 기반 Low-pass Filter를 적용하였습니다.

![Filter](images/troubleshooting_filter.png)
