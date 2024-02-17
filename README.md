# csr24w_cxray
Chest X-Ray Image Classification for SNU ExploreCSR 2023-24 Winter Workshop

## Overview
[CheXNet](https://github.com/arnoweng/CheXNet) 모델을 Chest X-ray의 COVID-19 감염 여부를 판단하는 태스크에 적용합니다. <br>
모델의 pre-trained weights 사용 여부, data augmentation 방식, optimizer type, parameter 개수 등의 변수들이 <br>
training efficiency와 accuracy에 끼치는 영향을 확인하고자 합니다.

### Model
[CheXNet](https://github.com/arnoweng/CheXNet)

### Datasets
[COVID Chest X-ray Dataset](https://github.com/ieee8023/covid-chestxray-dataset) <br>
[Pneumonia Chest X-ray Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

## Optimization Strategies
(TODO)

## Conventions
- main branch에는 직접 push 또는 commit하지 않고, PR merge를 통해 변경사항을 반영합니다
- branch name: `${task id}/${description(optional)}`
  - ex) `CSR-10`, `CSR-10/model`, `CSR-10/bugfix`
- commit message: `[${task id}]: description` 
  - ex) `[CSR-10]: model 구현` 
