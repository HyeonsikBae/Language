## Python Tuple

- Python에서 Tuple을 다루는 방법들에 대해 아래 예문을 통해 설명할 예정이다.

- tuple의 가장 큰 특징은 __tuple 값 변경을 허용하지 않는다__는 점이다 

  - 프로그래밍을 여러명이 관여할 때, constant한 값을 사용하기 위함이다.

- Variable 선언 CODE

  ```python
  tupleTest = (1, 2, 3)
  # tuple은 소괄호를 통해 선언한다.
  ```
  
- ex code 1

  ```python
  print(tupleTest)
  print(tupleTest[0], tupleTest[1], tupleTest[2])
  print(tupleTest[-1], tupleTest[-2])
  print(tupleTest[1:3])
  print(tupleTest + tupleTest)
  print(tupleTest*3)
  # String과 유사하게 tuple의 인덱스에 접근이 가능하다.
  ```
  
- ex result 1

  ```
  (1, 2, 3)
  1 2 3
  3 2
  (2, 3)
  (1, 2, 3, 1, 2, 3)
  (1, 2, 3, 1, 2, 3, 1, 2, 3)
```