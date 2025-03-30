# vicky-til

## 인공지능 프로젝트
### 주제: Image classification을 위한 Resnet기반 성능 향상 연구
- 10개의 데이터 중 세개 골라 모델 훈련 시키기
- 각 데이터에 최적화된 모델로 성능 향상 시키기
- 공부한 지식을 서로 나누며 같이 성장하기

### 개발 인원 및 기간
- 개발기간: 2025-03-17 ~ 2025-03-30
- 개발 인원: 1명(개인 프로젝트)

### 사용 기술 및 tools
- pytorch
- Grad-cam
- kaggle
- Mysql

### 프로젝트 Colab링크
- [rice_dataset_result]https://drive.google.com/file/d/17-DqnFSroya-ncU5WrMUv-9BSXQbUQxs/view?usp=sharing
- [pistachio_dataset_result]https://drive.google.com/file/d/1kZdwuDmpu0WCE3r5ZaQvnz3vcTjw6bDK/view?usp=sharing
- [flower_dataset_result]https://drive.google.com/file/d/1MPE5ZoPM9MYQBZkFJGlOamf0qwDs-iSX/view?usp=sharing

### 프로젝트 보고서 링크
- [보고서]https://docs.google.com/document/d/1oNPEphw66-1x9VCS0kZgG9-oQfDfcdyZUmzhpVUF7wA/edit?usp=sharing

### 프로젝트 결과 정리
- Test accuracy: 각 데이터 셋에서 100%, 99.69%, 95.40%로 높은 성능을 보임
- 경량화: resnet18을 사용하여 노트북 환경에서 mps장치로 빠르게 학습 진행.