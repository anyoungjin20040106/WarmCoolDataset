# 🎨 퍼스널 컬러 분석 시스템

## 📌 프로젝트 소개
이 프로젝트는 YOLOv11-CLS 모델을 기반으로 사용자의 얼굴 이미지에서 퍼스널 컬러(웜톤/쿨톤)를 자동으로 분류하는 AI 기반 시스템입니다. Unity AR 기능과 실시간 커뮤니티 기능을 통합하여 사용자 친화적인 서비스를 제공합니다.

---

## 🏗 시스템 구성
프로젝트는 다음 다섯 개의 주요 리포지토리로 구성되어 있습니다:

### 1. [WarmCoolYolo](https://github.com/anyoungjin20040106/WarmCoolYolo)
- YOLOv11-CLS 기반 퍼스널 컬러 분류 모델
- Roboflow를 통한 데이터셋 관리
- 모델 학습 및 평가 파이프라인

### 2. [WarmCoolFastapi](https://github.com/anyoungjin20040106/WarmCoolFastapi)
- FastAPI 기반 백엔드 서버
- YOLOv11-CLS 모델 서빙
- RESTful API 엔드포인트 제공
- Postgresql 데이터베이스 연동

### 3. [WarmCoolUnity](https://github.com/anyoungjin20040106/WarmCoolUnity)
- Unity 기반 AR 애플리케이션
- ARFoundation을 통한 얼굴 인식
- 가상 메이크업 적용
- Photon 기반 실시간 채팅

### 4. [WarmCoolSQL](https://github.com/anyoungjin20040106/WarmCoolSQL)
- 채팅 정보 관리
- 유저 정보 관리
- 퍼스널 컬러 해설

### 5. [WarmCoolDataset](https://github.com/anyoungjin20040106/WarmCoolDataset)
- roboflow를 활용한 데이터 수집
- github를 활용한 데이터 수집
- 데이터 라벨링


---


## 🛠 사용 기술

- ![Roboflow](https://img.shields.io/badge/-roboflow-6706CE?style=flat&logo=roboflow&logoColor=white)
- ![github](https://img.shields.io/badge/-github-000000?style=flat&logo=github&logoColor=white)

---

## 💻 기술 스택

- **AI/ML**: ![Ultralytics(YOLOv11-CLS)](https://img.shields.io/badge/YOLOv11--CLS-111F68?style=flat&logo=Ultralytics&logoColor=white)
- **백엔드**: ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white), ![docker](https://img.shields.io/badge/-docker-2496ED?style=flat&logo=docker&logoColor=white), ![amazonwebservices](https://img.shields.io/badge/-AWS%20AppRunner-232F3E?style=flat&logo=amazonwebservices&logoColor=white), ![amazonwebservices](https://img.shields.io/badge/-AWS%20Elastic%20Container%20Registry-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
- **DB** : ![Postgresql](https://img.shields.io/badge/-postgresql-4169E1?style=flat&logo=postgresql&logoColor=white), ![amazonrds](https://img.shields.io/badge/-amazonrds-527FFF?style=flat&logo=amazonrds&logoColor=white)
- **프론트엔드**: ![Unity(ARFoundation)](https://img.shields.io/badge/-ARFoundation-000000?style=flat&logo=unity&logoColor=white)
- **네트워킹**: ![Photon Chat](https://img.shields.io/badge/-Photon%20Chat-004480?style=flat&logo=photon&logoColor=white)
- **데이터 수집**: ![Roboflow](https://img.shields.io/badge/-roboflow-6706CE?style=flat&logo=roboflow&logoColor=white),![github](https://img.shields.io/badge/-github-000000?style=flat&logo=github&logoColor=white)
- **디자인**: ![Photoshop](https://img.shields.io/badge/-Photoshop-31A8FF?style=flat&logo=adobe-photoshop&logoColor=white)