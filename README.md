# 프로그래머스 모의고사

#### ⚙️ 00_순열_permutations.py
- 순열 구현 연습 by recursion
- 1회 4번, 2회 1번 푸는 데 필요
- 뭔가 더 효율적인 방법이 있지 않을까 생각해서 미뤄놨는데 책에 나와있는 거랑 같은 방법이었음 ..
- 미루지말고 풀자 ㅠ_ㅠ
- 그리고 조합이 남았음

#### ⚙️ 00_조합_combinations.py
- 조합 구현 연습 by recursion
- 2회 1번 푸는 데 필요
- 중복되는 것을 빼줘야함 > 앞 쪽에 있던 숫자는 다 지워주는 방식으로 처리 
- 책에 있는 방법은 그다지 이해가 잘 안 됨..
- 실수한 부분: 처음 만든 테스트 케이스를 1, 2, 3, 4, 5로 만들면서 착각했다! 예를 들어 3을 골랐으면 인덱스가 2번 앞에 있는 걸 지워주고 난 뒤에 남은 것들로 선택해야 된다. 1씩 증가하게 만들어서 인덱스가 아니라 3보다 작은 1, 2를 지워라로 접근해서 처음에는 조합을 만들때 5C2 != 10이 나오게 해버렸다.
- 처음에 엉뚱하게 풀었던 문제는 history에 남아있음


#### 📌 01_prob1_solution.py
- dict, sort (descending)
- x, y 두 개의 숫자를 입력받아 공통 숫자 찾기 & 만들 수 있는 가장 큰 수 만들기

#### 📌 01_prob2_solution.py
- dict, want list 안의 물건 종류 & 수량 -> discount calendar에서 살 수 있는 날을 찾아줘
- want, number, discount 입력받기

#### 📌 01_prob3_solution.py
- deque, stack
- 생성되는 택배를 실어라

#### ⌛ 01_prob4_ongoing.py
- 행 전체, 열 전체 뒤집기로 beginning에서 target으로 갈 수 있을까? 가능하다면 몇 번 뒤집어야될까?
- 모든 경우에 대해서 다 뒤집는 게 안 됨 -> 순열, 조합 연습 


#### test files라고 했지만 연습장 겸 쓰레기통
- 1st_prob3_z_trash_01.py
- 1st_prob3_z_trash_01debugging.py
- z_01_prob1_test.ipynb
