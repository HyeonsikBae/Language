## Python String

- Python에서 String을 다루는 방법들에 대해 아래 예문을 통해 설명할 예정이다.

- Variable 선언 CODE

  ```python
  strTest = 'Hyeonsik Bae'
  strTestComp = "Hyeonsik Bae"
  ```

- ex code 1

  ```python
  print(strTest, len(strTest))
  print(strTestComp, len(strTestComp))
  				# len을 통해 String의 길이를 알 수 있다.
  print(strTest == strTestComp)
  				# == 또는 != 을 통해 str 비교가 가능하다.
  print("sik" in strTest)
  print("sik" not in strTest)
  				# in, not in 을 통해 해당 변수내 값 여부를 알 수 있다.
  print(strTest * 2)
  				# * 연산을 통해 string을 반복 출력할 수 있다.
  ```
  
- ex result 1

  ```
  Hyeonsik Bae 12
  Hyeonsik Bae 12
  True
  True
  False
  Hyeonsik BaeHyeonsik Bae
  ```

- ex code 2

  ```python
  print(strTest[0], strTest[1], strTest[2])
    				# 양의 정수 인덱스 접근을 통해 다음 인덱스의 문자열 값을 알 수 있다.
  print(strTest[0], strTest[-1], strTest[-2])
    				# 음의 정수 인덱스 접근을 통해 역순 인덱스의 무자열 값을 알 수 있다.
  ```
- ex result 2

  ```
  H y e
  H e a
  ```

- ex code 3

  ```python
  print(strTest[1:5])
  				## [x:y]와 같은 인덱스 접근을 통해 특정 범위의 문자열 값을 알 수 있다.
  print(strTest[5:])
  				## [x:]와 같은 인덱스 접근을 통해 x부터 문자열 값을 알 수 있다.
  ```

- ex result 3

  ```
  yeon
  sik Bae
  ```

- ex code 4

  ```python
  print(strTest[1:9:2])
  print(strTest[1:len(strTest):2])
  				## [x:y:z]와 같은 인덱스 접근을 통해 x ~ y 범위의 값을 z step에 따라 알 수 있다.
  print(strTest[1::2])
  print(strTest[5::-1])
  				## [x::z]와 같은 인덱스 접근을 통해 x부터의 값을 z step에 따라 알 수 있다.
  ```

- ex result 4

  ```
  yosk
  yoskBe
  yoskBe
  snoeyH
  ```

  