# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김종환
- 리뷰어 : 김국화


# PRT(Peer Review Template)
- [V]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - text recognition을 위한 전처리 진행
        - <img width="942" alt="image" src="https://github.com/user-attachments/assets/a9a8d47f-cb78-4301-acd8-fb11028ac59f">
        - <img width="890" alt="image" src="https://github.com/user-attachments/assets/ccad34ad-f19b-47a5-9688-c4e060a8e49c">
        - CRNN 기반 결과
        - <img width="940" alt="image" src="https://github.com/user-attachments/assets/240a5957-9ec9-48d1-80b6-54ce1e48eb66">
        - <img width="940" alt="image" src="https://github.com/user-attachments/assets/a49df534-a94c-472a-96e5-ddf7b1706c96">
        - end-to-end 함수
        - <img width="885" alt="image" src="https://github.com/user-attachments/assets/27f7190d-a6bb-490a-b556-e2074becc5a6">


- [V]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 함수의 역할이나 사용 이유 기재
        - <img width="900" alt="image" src="https://github.com/user-attachments/assets/01d9d962-1613-4414-b289-c83d353933c2">

        
- [V]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 모델 별로 동일한 사진에 대한 결과 비교를 진행
        - <img width="923" alt="image" src="https://github.com/user-attachments/assets/8f8ca5c6-41db-458f-a949-7aa6de5afdee">

        
- [V]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 결과 분석 및 고찰 작성
        - <img width="735" alt="image" src="https://github.com/user-attachments/assets/d166081c-8e20-41b5-9936-7f3f6729d4b8">

        
- [V]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 시각화를 비롯해 대부분 함수화를 통해 재사용이 가능하도록 작성
        - <img width="889" alt="image" src="https://github.com/user-attachments/assets/f0a1c7de-28e3-4acc-b9a1-7d427bcdfe68">



# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```

각 모델 별로 결과를 시각적으로 비교해줘서 지루하지 않았다.
결과에 대한 분석에 모델 별로 아쉬운 점이라던가 성능 비교 등에 대해 언급해줘서 
코드 리뷰만으로도 배울 게 많았다. 
참고해서 내 코드도 개선시켜봐야겠다.

<img width="939" alt="image" src="https://github.com/user-attachments/assets/c56debb0-5a8a-4e1c-8557-3ee815f616eb">
