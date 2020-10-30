## Python if

- 파이썬에서 사용되는 for문을 아래 예시코드와 함께 설명.

- ex code 1

  ```python
  def main():
      for num in range(10):			# range(10) == [:10:]
          print(num)
      for num in range(1, 11):		# range(1, 11) == [1:11:]
          print(num)
      for num in range(1, 100, 10):	# range(1, 100, 10) == [1:100:10]
          print(num)
  # [x:y:z] : from 'x' to 'y' with step 'z'
  ```

- ex result 1

  ```
  0 1 2 3 4 5 6 7 8 9
  1 2 3 4 5 6 7 8 9 10
  1 11 21 31 41 51 61 71 81 91
  ```

- ex code 2

  ```python
  for num in range(5):
      print(num)
  else:					# for 문이 정상적으로 동작하고 끝났을 때, else 문 실행
      print("FINISH")
  for num in range(5):
      if num == 3:
          break
      print(num)
  else:
      print("FINISH")
  ```

- ex result 2

  ```
  0 1 2 3 4 FINISH
  0 1 2
  ```

- ex code 3

  