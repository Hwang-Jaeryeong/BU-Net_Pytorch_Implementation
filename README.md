# BU-Net_Pytorch_Implementation
🧠 Implementation of BU-Net with Pytorch<br>
(팀명 보강재 - [강지헌](https://github.com/heoneyzi), [권보영](https://github.com/iamnotwhale), [황재령](https://github.com/Hwang-Jaeryeong))


## 소개

인공지능 연합 프로젝트 팀 [deep daiv.](https://deepdaiv.oopy.io/)의 2024년 봄 기수 Medical AI 세션의 프로젝트로 진행된 **U-Net 기반 뇌 종양 이미지 분할** 프로젝트의 레포지토리입니다. <br>


## 사용 방법

### 데이터셋 준비

BraTS (Brain Tumor Segmentation) 2018 데이터셋을 사전에 준비해야 합니다. 데이터셋은 [여기](https://www.med.upenn.edu/sbia/brats2018/registration.html)를 통해 접근할 수 있습니다.


### 환경설정
모델 학습에 필요한 패키지를 설치해주세요.
```
python -m pip install -r requirements.txt
```

### 데이터 전처리
데이터셋을 준비한 이후에 preprocess 폴더 내의 `preprocess.py` 파일을 실행시켜 주세요.
#### Usage
```
cd preprocess
python preprocess.py --datapath --savepath
```

### 학습
```
python train.py
```

### 추론
```
python test.py
```


### Project 설명 페이지
https://chunsikk.tistory.com/8
