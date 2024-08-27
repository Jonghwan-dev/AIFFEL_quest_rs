# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김종환
- 리뷰어 : 윤철희 


# PRT(Peer Review Template)
- [O ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거 
        
        plt 그래프로 시각화와 head를 통해서 데이터의 feature들과 개수 값들을 시각화를 통해서 쉽게 볼 수 있었습니다. 
    
- [ x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부

        
         doc string/annotation 없음 
         
         bike sahjring 데이터에서 
         ```
         X = train.drop(columns=["datetime", "casual", "registered", "count"])
          y = train["count"]
         ```
          
          저 datetime, casual,registered, count feature들을 왜 drop 하신지 주석이 없습니다.
            
        ``
        def gradient(X, W, b, y):
        # N은 데이터 포인트의 개수
        N = len(y)
    
        # y_pred 준비
        y_pred = model(X, W, b)
    
        # 공식에 맞게 gradient 계산
        dW = (2/N) * X.T.dot(y_pred - y)
        
        # b의 gradient 계산
        db = 2 * (y_pred - y).mean()
        return dW, db
        ```
        각각의 공식이 어떤 의미인지 주석을 통해 보기가 좋습니다. 
        
        
- [ X ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
-  [ X ]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
        ```
        def model(X, W, b):
        `predictions = 0
        for i in range(10):
        predictions += X[:, i] * W[i]
        predictions += b
        return predictions
        ```
        추후에 다시 저 model 함수를 작성하지 않도록 function으로 작성해서 코드가 간결하고 효율적입니다. 

# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
    
```
         bike sahjring 데이터에서 
         ```
         X = train.drop(columns=["datetime", "casual", "registered", "count"])
          y = train["count"]
         ```
         이 부분에 대해서 어떠한 이유로 이 feature들을 drop하신지 주석으로 설명해 놓으시면 좋을거 같습니다.
      더 다양한 시도를 해보았으면 좋았을거 같습니다. (아직 그림 넣는 법을 모르겠어요)
