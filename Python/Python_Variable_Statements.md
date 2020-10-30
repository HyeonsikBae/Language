## Python Variable Statements

- Python에서 사용되는 변수의 자료형은 변수에 들어가는 값에 따라 달라진다.

- 자료형이 맞지 않아 발생하는 문제의 경우, type을 통해 자료형을 확인할 수 있다.

- CODE

  ```python
  def main():
      numYearBase10 = 2020
      numYearBase8  = 0o03744
      numYearBase16 = 0x7E4
      print ("Year by base 10 : ", numYearBase10, type(numYearBase10))
      print ("Year by base 8  : ", numYearBase8, type(numYearBase8))
      print ("Year by base 16 : ", numYearBase16, type(numYearBase16))
      
      numComplex1 = complex(3, 4)
      numComplex2 = 4 + 3j
      print ("Complex value   : ", numComplex2, type(numComplex2))
      print ("Absolute value  : ", abs(numComplex2), type(abs(numComplex2)))
      print ("Real value      : ", numComplex2.real, type(numComplex2.real))
      print ("Image value     : ", numComplex2.imag, type(numComplex2.imag))
  
      strFirstName = "Hyeonsik"
      strLastName = "Bae"
      print ("First Name      : ", strFirstName, type(strFirstName))
      print ("Full Name       : " + strFirstName + " " + strLastName,\
             type(strFirstName + strLastName))
  main()
  ```

- RESULT

  ```
  Year by base 10 :  2020 <class 'int'>
  Year by base 8  :  2020 <class 'int'>
  Year by base 16 :  2020 <class 'int'>
  Complex value   :  (4+3j) <class 'complex'>
  Absolute value  :  5.0 <class 'float'>
  Real value      :  4.0 <class 'float'>
  Image value     :  3.0 <class 'float'>
  First Name      :  Hyeonsik <class 'str'>
  Full Name       : Hyeonsik Bae <class 'str'>
  ```

  