# 2023_SW_AI_Contest
위성 이미지의 건물 영역 분할을 수행하는 AI모델

## 개요
 - 대회명 : DACON SW 중심대학 공동 AI 경진대회
 - 작업 기간 : 23.07.03 ~23.07.29 
 - 팀장 : 정동규
 - 개발자명 : 정동규 선주환 우진우 곽연규
 - 팀명 : 영대 MZ들
 - 소속 : 영남대학교 정보통신공학과

## 상세
 - 언어 : Python
 - 핵심 라이브러리 : torch, tensorflow, pandas, matplot

## 개발 다이어그램
- 기본적인 U-Net 모델을 이용하여 AI모델 구축
- 학습데이터와 실험데이터의 사진의 크기를 맞추기위해 학습데이터에서 Crop으로 resize
- 다양한 전처리 과정을 통하여 학습데이터 다양화 (사진반전, 밝기조절)
- CUDA 설정을 통한 GPU 사용법

## 결과
최종탈락

![0287_001_페이지_1](https://github.com/jdg824/2023_SW_AI_Contest/assets/80143957/11f4a17e-ee60-4c47-ab20-fdafc75398a2)
