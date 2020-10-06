---
layout: post
title:  "AIFFEL Hackathon - COVID19 양성 판별 모델 만들기(1)"
date:   2020-10-06 16:24
category: aiffel_hackathon
icon: 
keywords: 
image: 
preview: 0
---

# 해커톤 진행 상황 정리

## DataSet
- COVID 19 선행 논문 5개를 살펴본 결과 병원들이 소유하고 있는 private dataset은 접근이 불가능함
- 그 외 논문은 대부분 아래 공개된 데이터셋을 이용하여 접근하고 있었음
- 방사선사에 의해 라벨링 된 데이터라 신뢰성이 있다고 판단한거 같음

## 데이터셋 링크들
🚩 Reference Dataset

1️⃣ ChestXray14 (112000 images of 14 diseased and normal CXR images)
https://nihcc.app.box.com/v/ChestXray-NIHCC

2️⃣ RSNA Pneumonia Detection Challenge’
https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/data

3️⃣ Chest X-Ray Images Pneumonia
https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

4️⃣ COVID-19 Image
https://github.com/ieee8023/covid-chestxray-dataset

5️⃣ Audio Dataset
https://github.com/iiscleap/Coswara-Data
https://www.covid-19-sounds.org/en/
https://github.com/virufy/covid

6️⃣ Other
https://github.com/haydengunraj/COVIDNet-CT
https://github.com/ieee8023/covid-chestxray-dataset

These are links to sample dataset for reference purpose only. Participants are free to use these or other datasets after studying respective licenses

🚩 Prior Work/Reference

1️⃣ https://www.quantib.com/blog/ai-for-covid-19-radiology
2️⃣ https://pubs.rsna.org/doi/10.1148/radiol.2020200905
3️⃣ https://arxiv.org/pdf/2003.09871.pdf

## COVID 특징들

- 현재 검사 방법은 고가, 대면 검사의 위험성, 시간이 오래걸리는 단점을 가지고 있음

- 보통 초기 COVID 19는 흉부 X-ray에서는 잘 보이지 않는다는 소견이 많아 CT가 보편적으로 사용되는 것으로 생각됨

- 현재 CT, X-ray 데이터셋을 어떻게 조합하여 classification을 하는지에 대해 소개하고 있는 논문 리뷰 예정(현수님)


