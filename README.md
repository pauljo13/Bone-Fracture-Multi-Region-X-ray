# 💀 Bone Fracture Multi-Region X-ray to Pytoch
start : 2024-05-20  
end :  

---

## Content
- Project abstract
- Introduction
    - X-ray
    - Bone Fracture Multi-Region
    - Deep Learning
    - Image Classification
    - Pytoch
- Materials and Methods
    - Materials
    - Methods
        - EDA
        - Data split
        - Model definition
        - Model tuning
        - Final model
        - Make web page
            - make DB
            - HTML & CSS
            - page service
- Results
- Discussion
- Conclusion
- References

--- 
## Project abstract



---
## Introduction
### X-ray
X-ray는 전자기 스펙트럼의 일부로, 주로 의료 분야에서 뼈, 이물질, 폐의 상태를 평가하는 데 사용됩니다. X-ray 이미지는 전자기 방사선이 몸을 통과한 후, 뼈나 금속 같은 밀도가 높은 물질에 의해 흡수되거나 반사되어 생성됩니다. 이를 통해 내부의 구조와 이상을 확인할 수 있습니다.   

### Bone Fracture Multi-Region
다부위 골절은 환자의 여러 해부학적 위치에서 동시에 발생하는 골절을 의미합니다. 이러한 골절은 교통사고나 높은 곳에서의 추락 등의 중대한 사고로 인해 발생할 수 있으며, 종종 다발성 부상의 일환으로 관리됩니다.  

### Deep Learning
딥러닝은 인공 신경망을 사용하여 복잡한 패턴과 데이터를 학습하는 기계 학습의 한 분야입니다. 다수의 은닉 계층을 통해 높은 수준의 추상화를 달성할 수 있으며, 이미지 인식, 음성 인식, 자연어 처리 등 다양한 분야에서 활용됩니다.  

### Image Classification
이미지 분류는 주어진 이미지를 사전 정의된 카테고리 중 하나로 분류하는 과정입니다. 이 과정은 딥러닝 모델을 훈련시켜 각 이미지에 대한 정보를 추출하고, 이를 기반으로 클래스 레이블을 할당합니다. 의료 영상, 위성 사진 분석, 동물 분류 등 다양한 분야에서 사용됩니다.  

### Pytoch
PyTorch는 오픈 소스 머신 러닝 라이브러리로, 주로 딥러닝 응용 프로그램과 연구에 사용됩니다. 그 특징은 강력한 GPU 가속, 동적 계산 그래프를 제공하며, 빠른 프로토타입 제작과 연구를 용이하게 합니다.  



## Materials and Methods
### Materials
 os, Numpy, Pandas, Image, Matplotlib, Seaborn, Pytorch
  

### Methods
#### EDA
##### 데이터 확인
데이터를 직접 유관으로 확인, 데이터 확인 결과 train, test, val 파일에 각각 fractured와 No fractured가 존재함 No fractured가 정상인의 X-ray 이미지, fractured에 골절 X-ray이미지가 존재 했다. 이미지들은 이름과 사이즈가 제각각으로 확인데 데이터 관리를 위해 이미지 이름을 수정한다.
이미지의 이름과 이미지의 크기 taget으로 데이터 프레임을 만들어 데이터를 쉽게 볼 수 있도록 만든다.
train :  4604, 4640 개  
val :  337, 492 개  
test : 238, 268 개  
로 총 10579개 가 존재한다.
fractured와 No fractured의 비율은 49.0%(5179) 대 51.0%(5400) 이다.
  
##### 데이터 전처리
이미지 사이즈는 width와 height는 최소 사이즈가 100 pixels 최대 사이즈는 width는 4232 pixels height는 5823 pixels이다. 평균 width는 299.7 pixels height는 325.03 pixels이다. 그래서 이미지의 크기를 일정하게 만들어주는 전처리 과정을 가져야 한다. 
딥러닝의 최적인 사이즈 224x224로 패딩을 사용한다.
  
#### Data split
#### Model definition
#### Model tuning
#### Final model
#### Make web page



## Results



## Discussion



## Conclusion



## References