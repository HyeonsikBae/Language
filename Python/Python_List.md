## Python List

- Python에서 List를 다루는 방법들에 대해 아래 예문을 통해 설명할 예정이다.

- Variable 선언 CODE

  ```python
  listTest = [1, 3, 2, 4]
  listForSort = [1, 5, 2, 7, 5, 2]
  # list는 대괄호를 통해 선언한다.
  ```

- ex code 1

  ```python
  print(listTest)
  print(listTest[0], listTest[1], listTest[2])
  print(listTest[-1], listTest[-2])
  print(listTest[1:3])
  print(listTest*3)
  # String과 유사하게 List의 인덱스에 접근이 가능하다.
  ```
  
- ex result 1

  ```
  [1, 3, 2, 4]
  1 3 2
  4 2 
  [3, 2]
  [1, 3, 2, 4, 1, 3, 2, 4, 1, 3, 2, 4]
  ```

- ex code 2

  ```python
  print(4 in listTest, 100 in listTest)
  # String과 마찬가지로 in, not in을 통해 특정값이 리스트 내에 존재하는지 확인할 수 있다.
  ```

- ex result 2

  ```
  True False
  ```

- ex code 3

  ```python
  listTest.append('hey')
  print(listTest)
  # append method를 통해 list에 값 추가가 가능하다.
  del listTest[0]
  print(listTest)
  # del 을 통해 특정 인덱스 값 삭제가 가능하다.
  listTest.remove(4)
  print(listTest)
  # remove method를 통해 특정 값 삭제가 가능하다.
  listTest.reverse()
  print(listTest)
  # reverse method를 통해 list 순서를 뒤집을 수 있다.
  listForSort.sort()
  print(listForSort)
  # sort method를 통해 list를 정렬할 수 있다. 다른 type끼리는 Error가 발생한다.
  ```

- ex result 3

  ```
  [1, 3, 2, 4, 'hey']
  [3, 2, 4, 'hey']
  [3, 2, 'hey']
  ['hey', 2, 3]
  [1, 2, 2, 5, 5, 7]
  ```