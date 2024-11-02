# javascript-lotto-precourse

## 기능 목록

- [ ] 로또 구입 금액 입력 기능
  - 1,000원 단위의 금액을 입력
  - 금액이 1,000원으로 나누어 떨어지지 않는 경우 에러 메시지 출력 및 재입력 요청
- [ ] 구입 금액에 따른 로또 발행 기능
  - 구입 금액에 따라 발행할 로또 개수를 계산
  - 각 로또는 1에서 45 사이의 중복되지 않는 6개의 숫자로 구성
  - 생성된 로또 번호는 오름차순으로 정렬하여 출력
- [ ] 당첨 번호 입력 기능
  - 쉼표로 구분된 6개의 숫자를 입력받아 저장
  - 입력된 숫자는 1에서 45 사이여야 하며, 중복이 없어야 함
  - 입력 형식이나 범위에 맞지 않으면 에러 메시지 출력 후 재입력 요청
- [ ] 보너스 번호 입력 기능
  - 보너스 번호를 입력받아 저장
  - 보너스 번호는 1에서 45 사이여야 하며, 당첨 번호와 중복되지 않아야 함
  - 입력 형식이나 범위가 맞지 않으면 에러 메시지 출력 후 재입력 요청
- [ ] 당첨 내역 통계 계산 기능
  - 사용자가 구매한 각 로또 티켓을 당첨 번호 및 보너스 번호와 비교하여 일치하는 개수를 계산.
  - 1등부터 5등까지의 당첨 조건에 맞는 로또 개수를 기록.
- [ ] 수익률 계산 기능
  - 당첨 내역에 따라 총 당첨 금액을 바탕으로 수익률 계산.
- [ ] 최종 통계 출력 기능
  - 당첨 내역과 수익률을 출력.
  - 당첨 내역은 각 등수별 당첨 개수를 포함하여 출력.
  - 수익률은 소수점 둘째 자리에서 반올림하여 출력.
