# Battery 산업 분석

- 2차 전지에 대한 전반적인 공부 하고 싶다면? [Youtube 영상 링크](https://www.youtube.com/watch?v=O8iWIgYZjik&list=PL4l1uLbAxhANO6Ov3FF59keNC1dgS_RIa&index=3)
- 2차 전지 공정은 크게 전극(극판) 공정(30%), 조립 공정(17%), **충방전(화성)공정(29%)**, 기타 공정(24%)으로 나뉩니다.
- 전극과 조립 공정까지 완료된 배터리(전지)는 있다 *아직* 전기를 띠지 않기 때문에, **전지의 역할**을 할 수 있도록 만들어 주는 단계가 바로 **화성공정** 입니다.


<img src="https://github.com/sooeun67/battery/blob/main/images/process_overview.png" alt="drawing" style="width:600px;"/>


# 화성 공정
### **배터리 충방전 및 에이징을 통해서 전지를 활성/안정화 시키는 공정**
- 전반적인 공정의 마지막 단계(전극 -> 조립 -> 화성)이며, 전체 공정의 약 29%를 차지
- 충방전 공정 혹은 활성화 공정이라고도 함
- 배터리 셀에 전기적 특성을 부여해 활성화시키고, 전지의 안정화 작업 후 결함 검사 및 배터리 등급을 부여하는 공정
- 세부적으로 **Formation -> Aging -> IR/OCV -> Grading/Selecting 공정**으로 나눠집니다.
- 공정 거의 대부분이 **자동화** 되어 있고 **빠른 충전 속도**와 **안정화 기술**이 중요한 공정
- 주요 기업
  -  국내: 원익피앤이(전 피앤이솔루션), 에이프로, 엠플러스, 엔에스
  -  중국: 한커


<img src="https://github.com/sooeun67/battery/blob/main/images/formation_process_overview.png" alt="drawing" style="width:600px;"/>


----------



# 1. Formation (충방전) 공정
### 전지를 충전해 방전 상태의 전지를 활성화시켜 전기적 특성을 부여하고, 방전용량을 검사하는 과정

- 규모
  -  화성 공정 전체 80% 비용 차지
  -  연간 3조원 시장 규모

- 최초 충전 공정으로 방전 상태의 셀을 활성화 시키는 공정으로, 이 때 음극 표면에 이온 전도성 얇은 고체막 즉, SEI(SEI, Solid Electrolyte Interphase) 층(Layer)이 형성됨
- 형성된 이 음극 층이, 리튬 이온을 전달하고 전해액과 리튬의 직접적인 접촉을 막아줘서 리튬 금속읭 부식 방지하는 역할을 함

- 고체전해질중간물질(SEI, Solid Electrolyte Interphase) 층(Layer)란?
    -  리튬 이온을 전달하고 전해액과 리튬의 직접적인 접촉을 막아줘서 리튬 금속읭 부식 방지하는 역할
    -  SEI가 얼마나 잘 생성되느냐에 따라 배터리 성능 및 수명을 결정하게 됨
   
    -  SEI가 불균일하게 형성되거나 국부적으로 집중되어 두껍게 쌓이게 되면 전해액과의 접촉을 증가시켜 전해액과 리튬 간 SEI 생성 반응이 지속적으로 발생하고, 이는 전해액과 리튬을 빠르게 고갈시키고 전지의 저항을 증가시켜 충전 속도와 용량을 낮추는 문제 발생

    -  즉 SEI 층이 배터리의 수명과 충방전 사이클 성능에 중요한 역할을 수행하므로 이를 안정적으로 조절하는 연구들이 지속되고 있음


- Formation 공정 장비는 빠르고 안정적으로 충방전을 수행하는 기술과 전압과 전류를 정밀하게 제어하는 기술 및 방전 시 사용되는 에너지를 재사용하여 에너지 효율을 높이는 기술 필요







# 2. Aging 공정
### 배터리를 정해진 온도나 습도에서 일정 시간 동안 보관해 배터리 내부에 전해액을 충분히 분산시켜 이온 이동의 최적화 상태를 만드는 공정

- 자연 방전 특성을 측정하기 위해 장기간 전지를 보관 해야하는데 이로 인해 공정 기간이 길어지고 보관 장소 증가 등의 비용 증가로 이어지기 때문에 Aging 기간을 단축시키는 것이 중요


# 3. IR/OCV 공정
### Aging된 2차 전지의 내부저항 분석과 개방 회로 전압 측정으로 배터리 품질을 평가하고 선별하는 공정

## 3-1. IR(Internal Resistance)
- Formation 및 Aging 공정의 전후에 여러번 수행됨
- 배터리 내부저항(IR)은 외부 인가되는 전류에 의해 전압을 상승 또는 강하시키게되는데, 이는 충방전 효율에 큰 영향을 주기 때문에, 내부저항이 작을수록 전지 성능이 좋음


## 3-2. OCV(Open Circuit Voltage)
- 개방회로전압 측정(OCV)은 배터리의 방전 시 양음극 간 미세단락 여부를 확인하기 위해 사용
- 미세단락이 생기면 배터리의 개방전압이 미세하게 변하는데, 변화량이 매우 작기때문에 측정을 위해서는 방전 시간이 길어져야 함
- OCV 측정기의 정확도와 정밀도가 좋을수록 방전 시간을 줄여 전체 공정 효율을 높일 수 있음

# 4. Grading/Selecting 공정
### 앞의 Formation, Aging, IR/OCV 공정을 통해 얻은 데이터를 통해 배터리 셀의 양/불 판정하고, 품질 별로 등급을 자동으로 분류해주는 공정

-------

# Reference
- https://blog.naver.com/sdibattery/220648736677
- https://seongyun-dev.tistory.com/16
- https://seongyun-dev.tistory.com/20
- https://greatluckim.tistory.com/31
- https://minggumanggu.tistory.com/entry/2%EC%B0%A8-%EC%A0%84%EC%A7%80%EC%9D%98-%EC%A0%9C%EC%A1%B0-%ED%94%84%EB%A1%9C%EC%84%B8%EC%8A%A43-%ED%99%94%EC%84%B1-%EA%B3%B5%EC%A0%95
- https://www.youtube.com/watch?v=O8iWIgYZjik&list=PL4l1uLbAxhANO6Ov3FF59keNC1dgS_RIa&index=3
 



