# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김종환
- 리뷰어 : 정서연


# PRT(Peer Review Template)
- [ㅇ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/94dafb0a-e5e5-43d9-89af-669f1e4ec97a)
        - 모델 설계 후 loss 값을 시각화하여 나타내었습니다.
        - ![image](https://github.com/user-attachments/assets/14e1a7ff-6ca1-4441-b939-6c780d429807)
        - 추상적 요약에서 실제 결과와 요약문을 잘 비교하여 나타내었습니다.
        - ![image](https://github.com/user-attachments/assets/8b15206f-d830-4ed8-9a22-980301fed404)
        - summa를 이용한 추출적 요약에서 실제 결과와 요약문을 잘 비교하여 나타내었습니다.
        - 



    
- [ㅇ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/caed840e-eac7-4950-ac0c-c5bd100c57a0)
        - 전처리 단계에서 각 코드별로 어떤 문자를 처리했는지 주석을 달아 구체적으로 잘 설명하였습니다.
        - ![image](https://github.com/user-attachments/assets/14c9e8f4-28e3-4ebb-a843-39f9a015a85e)
        - ![image](https://github.com/user-attachments/assets/f60a0c24-e909-4b52-b066-a16b279468f3)
        - ![image](https://github.com/user-attachments/assets/e5501315-b471-471a-8258-6cd19d799c07)
        - ![image](https://github.com/user-attachments/assets/baf74276-4f22-4cef-8802-d13711c447b9)
        - 위의 이미지처럼 코드를 짤 때 각 단계별 흐름을 잘 나타내어주어 보기가 편했습니다.
        - ![image](https://github.com/user-attachments/assets/47de28a6-3378-4db6-83a3-04d8f3598284)
        - stopwords 외에도 대문자를 소문자로 쉽게 처리할 수 있는 wordnet, omw-1.4와 같은 다른 기능도 다양하게 사용하는 실험을 하였습니다.
        - ![image](https://github.com/user-attachments/assets/89c4191d-ab2a-424b-ad4c-768be46ddb44)
        - 텍스트 길이를 파악하기 위해 박스플랏을 그린 뒤 적절한 사분위 해석 및 데이터의 크기가 많지 않다는 점을 고려하여 적절한 텍스트 길이값을 도출했습니다. 이후, 약 99퍼센트에 가깝게 데이터가 포함되어 있다는 것을 확인하였습니다.
        - 
        
- [ㅇ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/b7c554c5-75ed-41f2-8532-edf61a42acb1)
        - earlystopping 외에도 checkpoint callback 등을 다양하게 사용하여 모델을 최적화하는 것을 시도하였으나 시간이 부족하여 결과를 도출하진 못하였습니다.
        - ![image](https://github.com/user-attachments/assets/3f052eab-0046-468c-906a-dac20cf617a4)
        - rouge 평가지표를 사용하여 수동적으로 요약문과 결과값을 비교하는 것이 아니라 유니그램 끼리 비교할 수 있는 방법을 제시하였습니다.
        - ![image](https://github.com/user-attachments/assets/489c9dca-5fbb-49a0-81da-47860146b07f)
        - 모델 설계 과정에서 과적합을 막기 위하여 dropout 값을 실험을 통해 0.2로 최적화하며 매개변수를 수정하였습니다.

        
- [ㅇ]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/2c053bf6-8d5b-451c-83f2-38462abe5f57)
        - ![image](https://github.com/user-attachments/assets/96babe36-cb1c-4c0b-8225-0bcb949eb9a9)


- [ㅇ]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/30c4edac-c4f7-4299-abce-6a891e97b954)
        - 함수, 반복문 등을 사용하여 코드를 최소화하였습니다.



# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
--------------------------------------------------------------
종환님의 코드 리뷰를 들으면서, 노드에서 봤던 기능 외에도 다양한 전처리 기법이 있다는 것을 알게되었습니다.
그리고 실험을 통해 dropout 등의 매개변수를 최적화 하는 방법을 잘 설명해주셔서 이해가 잘 되었고,
earlystopping에서 patience의 개념이 헷갈렸는데 이에 대해서도 예시를 들어 잘 설명해주었습니다.
마지막으로, 평가할 때 직접 눈으로 일일이 비교하는 것이 아니라 rouge 평가지표를 제시하여 주셔서
유니그램 끼리 비교하는 방법도 있다는 것을 알게 되어 유익했습니다.

