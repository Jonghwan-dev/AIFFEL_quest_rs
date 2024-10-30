# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김종환
- 리뷰어 : 최세영


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/a0596185-b4e8-4e9a-af6a-315a29554c14)
        - ![image](https://github.com/user-attachments/assets/851a0d36-fa2b-408b-bc4a-4148f1f321e5)
        - ![image](https://github.com/user-attachments/assets/71a8c323-5223-495b-80c3-aa9d56bdd7db)
        - UNet / UNet ++ 두 모델에 대해 학습을 잘 진행하였고, 성능을 서로 잘 비교했습니다.

- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/c751631b-dd38-429a-ad6b-087215e7e2a8)
        - 모델 구성을 위해 각 블록 (path) 을 함수화 하는 과정에서 어떤 의미인지 잘 설명해두었습니다.

        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/d0326878-fb08-4767-a62d-978eb5e41bdd)
        - 위의 결과 분석을 토대로 아래의 실험을 진행했습니다.
        - ![image](https://github.com/user-attachments/assets/44de1ffd-98d9-47c3-8b36-7b695fca120b)
        - 이렇게 augmentation에서 밝기 및 대비 조절을 추가해주어 학습하여
        - ![image](https://github.com/user-attachments/assets/b11c550d-b718-4d41-9221-618108ec2ce9)
        - UNet ++의 성능을 올렸습니다.
        
- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/c6e51574-7657-4eff-9fc7-25396564bd32)
        - 회고를 적절히 잘 작성하셨습니다.

        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/43651b21-72b4-41d9-a512-f8a56a1ef552)
        - 모든 것이 함수화되어 중복된 코드를 최소화하였습니다. 특히 모델 구축을 위한 코드 블럭을 함축적으로 잘 표현한 것 같습니다.

# 회고(참고 링크 및 코드 개선)
```
되게 깔끔하게 정리를 잘 하셨고, 실험 진행이나, 실험 결과 시각화를 특히 잘해주신 것 같습니다. 대단합니다!
```
