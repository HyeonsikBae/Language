## Python if

- 파이썬에서 사용되는 if문을 아래 예시코드와 함께 설명.

- CODE

  ```python
  def main():
      num # 아래 결과에서 조건 제시
      if num > 90:
          print("Good")
      elif num > 70:
          print("Pass")
      else:
          print("Fail")
  ```

- RESULT

  ```
  num = 95 > Good
  num = 82 > Pass
  num = 66 > Fail
  ```

- 다른 언어에서도 쓰이는 if 문의 생김새가 조금 다르다.

- if : 다른 언어의 if 와 동일

- elif : 다른 언어에선 주로 else if 를 사용하지만 파이썬에선 elif 로 사용

- else : 다른 언어의 else와 동일