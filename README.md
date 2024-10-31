# javascript-lotto-precourse   
우아한 테크코스 프리코스 3주차 fork   
## 📜 3주차 구현 할 기능 목록   
&emsp; ⚫ 로또 구입 금액을 입력받는 기능   
&emsp; &emsp; ➖ 구입 금액은 1000원 단위로 입력 받는다.   
&emsp; &emsp; ➖ 1000원으로 나누어 떨어지지 않으면 예외처리 한다.   

&emsp; ⚫ 입력받은 로또 구입 금액으로 살 수 있는 만큼 로또를 발행하는 기능   
&emsp; &emsp; ➖ 로또 1장의 가격은 1000원이다.   
&emsp; &emsp; ➖ 로또 번호의 숫자 범위는 1 ~ 45 이다.   
&emsp; &emsp; ➖ 로또 번호는 6개의 숫자이고 서로 중복되지 않아야 한다.   

&emsp; ⚫ 당첨 번호를 입력받는 기능   
&emsp; &emsp; ➖ 당첨 번호는 6개의 숫자이고 서로 중복되지 않아야 한다.   
&emsp; &emsp; ➖ 번호는 쉼표(,)를 기준으로 구분한다.

&emsp; ⚫ 보너스 번호를 입력받는 기능   

&emsp; ⚫ 발행한 로또의 수량, 번호를 출력하는 기능   
&emsp; &emsp; ➖ 로또 번호는 오름차순으로 정렬해서 보여준다.

&emsp; ⚫ 당첨 내역을 출력하는 기능   
&emsp; &emsp; ➖ 당첨은 1 ~ 5등까지 있다.   
&emsp; &emsp; ➖ 1등: 번호 6개 일치 / 2000000000원   
&emsp; &emsp; ➖ 2등: 번호 5개 일치 + 보너스 번호 일치 / 30000000원   
&emsp; &emsp; ➖ 3등: 번호 5개 일치 / 1500000원   
&emsp; &emsp; ➖ 4등: 번호 4개 일치 / 50000원   
&emsp; &emsp; ➖ 5등: 번호 3개 일치 / 5000원   

&emsp; ⚫ 수익률을 출력하는 기능   
&emsp; &emsp; ➖ 수익률은 소수점 둘째 자리에서 반올림한다.

&emsp; ⚫ 예외 상황 시 에러 문구를 출력하는 기능   
&emsp; &emsp; ➖ 에러 문구는 '[ERROR]'로 시작해야한다.

## 📜 ERROR 케이스   
&emsp; ❌ 로또 구입 금액이 1000으로 나누어 떨어지지 않는 경우   
&emsp; ❌ 로또 구입 금액이 숫자가 아닌 경우   
&emsp; ❌ 로또 구입 금액을 입력하지 않은 경우   
&emsp; ❌ 당첨 번호 입력 시 6개의 숫자를 입력하지 않은 경우   
&emsp; ❌ 당첨 번호 입력 시 범위 외의 숫자를 입력한 경우   
&emsp; ❌ 당첨 번호 입력 시 쉼표가 아닌 다른 구분자를 입력한 경우   
&emsp; ❌ 당첨 번호 입력 시 숫자가 아닌 값을 입력한 경우   
&emsp; ❌ 당첨 번호 입력 시 중복되는 숫자를 입력한 경우   
&emsp; ❌ 보너스 번호 입력 시 범위 외의 숫자를 입력한 경우   
&emsp; ❌ 보너스 번호 입력 시 숫자가 아닌 값을 입력한 경우   
&emsp; ❌ 보너스 번호를 입력하지 않은 경우   