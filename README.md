# ChestXray-Pneumonia-Classification
흉부 X-ray 폐렴 분류 프로젝트

## 프로젝트 개요
- 폐렴과 정상 흉부 X-ray 이미지 분류하는 CNN 모델 개발
- Kaggle Chest X-ray Pneumonia 데이터셋 사용

## 데이터셋
- [Chest X-ray Pneumonia Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

## 기술 스택
- Python, PyTorch
- torchvision.models (ResNet18)

## 실행 방법
1. 데이터 다운로드 후 `data/` 폴더에 저장
2. 필요한 라이브러리 설치: `pip install -r requirements.txt`
3. 학습 실행: `python src/train.py`
4. 평가 실행: `python src/evaluate.py`

## 주요 결과
- 정확도, 혼동 행렬 시각화 이미지 첨부
- Grad-CAM 결과로 모델 해석 가능

