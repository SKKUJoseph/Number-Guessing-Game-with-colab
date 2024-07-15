# Number-Guessing-Game-with-colab

숫자 맞추기 게임
이 프로젝트는 Python을 사용한 간단한 숫자 맞추기 게임입니다. 사용자는 1부터 100 사이의 숫자를 맞춰야 하며, 컴퓨터는 사용자가 숫자를 맞출 때까지 힌트를 제공합니다.

 1. Colab 환경 설정

Google Colab에 접속하여 새 노트북을 생성합니다.
Python 코드 셀과 텍스트 셀을 추가합니다.
  2. 게임 Logic 작성

컴퓨터가 1부터 100 사이의 랜덤 숫자를 선택합니다.
 [참고] import random
            random.randint(1, 100)
사용자가 숫자를 입력하면 컴퓨터가 입력된 숫자와 랜덤 숫자를 비교합니다. (관계 연산자 사용)
사용자가 숫자를 맞출 때까지 힌트를 제공합니다 (예: "더 큰 숫자입니다.", "더 작은 숫자입니다.").
사용자가 숫자를 맞추면 축하 메시지를 출력하고, 게임을 종료합니다.
  3. 함수 작성

랜덤 숫자를 생성하는 함수  
사용자 입력을 받는 함수  
입력된 숫자를 검사하는 함수  
  4. 게임 실행

위의 함수를 사용하여 게임을 실행합니다.
