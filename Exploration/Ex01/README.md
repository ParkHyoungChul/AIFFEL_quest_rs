# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 박형철
- 리뷰어 : 진수민


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인!
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - pb1에 대해
        - ![image](https://github.com/user-attachments/assets/157a0a28-a0e6-4eab-a106-10973b88a568)
        - ![image](https://github.com/user-attachments/assets/31662707-814b-4003-81c6-ae6edb7b2938)
        - 좋은 결과값을 나타내기 위해 상관계수 확인 추가 진행
        - ![image](https://github.com/user-attachments/assets/a76ac124-784d-492d-8f66-1eb1f5b3a028)
      
        - pb2에 대해
        - ![image](https://github.com/user-attachments/assets/e3cc3807-4402-40df-be3b-03bec8a2f2fc)
          



    
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - pb1에 대해
        - 속성 변수에 대한 정보 doc
        - ![image](https://github.com/user-attachments/assets/8234f1d9-0ea7-4edd-87bd-5f4686e002ec)
        - loss 값에 대한 학습률 history : ** 가장 인상깊었음 **
        - ![image](https://github.com/user-attachments/assets/f0f3d212-7336-4c69-9bc9-cf79f707d5f9)
          

        
- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [X]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 모듈화가 잘 되었음.
        - ![image](https://github.com/user-attachments/assets/bb683179-9971-4a8a-8b04-35124a6de583)
        - 함수화가 잘 됨 : 범용적으로 사용 할 수 있도록 W의 len으로 받아서 사용
        - ![image](https://github.com/user-attachments/assets/e19b40ac-cab8-457d-887f-92aba29167c9)




# 회고(참고 링크 및 코드 개선)
```
짧은 코드이기에 파이썬 스타일 가이드에 대한 코멘트가 크게 없었음. 코드를 간결화 하고 범용적으로 사용 할 수 있도록 수정한 부분이 보여 이에 대한 코멘트를 남김.
pep8에 관한 ref : https://peps.python.org/pep-0008/
```

