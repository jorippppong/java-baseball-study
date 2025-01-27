## ⚾️ 기능 요구 사항 정리

### 랜덤 숫자 생성
- [x] 1~9 사이의 서로 다른 3자리 정수 생성

### 사용자 입력 처리
- [x] 잘못된 형식의 값을 입력 → 예외 발생 & 프로그램 종료
  - 잘못된 형식의 입력
    - [x] 입력이 정수가 아님
    - [x] 같은 숫자가 반복
    - [x] 3자리
- [x] 올바른 형식의 값을 입력 → 게임 진행

### 게임 힌트 제공 방법
- [x] 플레이어와 컴퓨터의 값을 비교해서 값 처리
- [x] 처리한 값을 기준으로 S, B, N 판단
- [x] 정답 → 완료 문구 출력 & 게임 종료 처리
- [x] 오답 → 플레이어에게 다시 입력 받음

### 게임 종료 시 처리 방법
- [x] 1 입력 → 게임 다시 시작
- [x] 2 입력 → 게임 종료
- [x] 이 둘을 제외한 다른 입력 → 예외 처리 & 프로그램 종료