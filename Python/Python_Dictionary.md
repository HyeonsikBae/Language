## Python Dictionary

- Python에서 Dictionary를 다루는 방법들에 대해 아래 예문을 통해 설명할 예정이다.

- Dictionary의 가장 큰 특징은 __key : value__ 형태의 값을 이용한다는 점이다 

- Variable 선언 CODE

  ```python
  dicTest = {1:'one', 2:'two', 3:'three'}
  # tuple은 중괄호를 통해 선언한다.
  ```
  
- ex code 1

  ```python
  print(dicTest)
  print(dicTest[1], dicTest[2], dicTest[3])
  # dictionary는 인덱스가 아닌, key 값에 접근한다
  ```
  
- ex result 1

  ```
  {1: 'one', 2: 'two', 3: 'three'}
  one two three
  ```
  
- ex code 2

  ```python
  dicTest[2] = 'TWOTWO'
  # dictionary는 key 값에 접근하여 value 값 변경이 가능하다.
  print(dicTest)
  ```

- ex result 2

  ```
  {1: 'one', 2: 'TWOTWO', 3: 'three'}
  ```

- ex code 3

  ```python
  print(dicTest.keys())
  print(dicTest.values())
  print(dicTest.items())
  # dictionary는 key, value, item에 각각 접근이 가능하다.
  ```

- ex result 3

  ```
  dict_keys([1, 2, 3])
  dict_values(['one', 'TWOTWO', 'three'])
  dict_items([(1, 'one'), (2, 'TWOTWO'), (3, 'three')])
  ```