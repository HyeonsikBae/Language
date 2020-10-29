## Python Structure

- 주석

  - 앞으로 정리할 파이썬 코드에 주석을 달 예정이므로 파이썬에서 주석을 다는 방법을 아래 설명하겠다.
  - 한 줄 주석 : #
  - 여러 줄 주석 : ''' or """

- Indentation

  - 들여쓰기를 기준으로 블록 구분

- 구조 (Procedure 기반)

  - CODE

    ```python
    class HelloPython():
    # HelloPython 이라는 class 정의
        def __init__(self):
            print("INIT")
        # __init__ 이라는 method 정의.
        # parameter에 self가 들어가면 자기자신을 의미.
        # 해당 클래스가 instanciation 시에 __init__ method가 실행된다.
        def __del__(self):
            print("DEL")
        # __del__ 이라는 method 정의.
        # 해당 클래스의 instanciation이 없어질 시에 __del__ method가 실행된다.
        def perform(self, var1, var2):
            print("HELLO PYTHON !")
            print((var1 + var2) / 2.0)
        # __perform__이라는 method 정의
    def main():
    # main 문 정의
        python = HelloPython()
        '''
        python - instance를 storage하는 variable
        HelloPython() - instance를 만들어내는 instance template (Class)
        '''
        python.perform(2, 4)
        # python instance의 perform method 실행.
    main()
    # main 문을 불러와서 실행.
    ```

  - RESULT

    ```
    INIT
    HELLO PYTHON !
    3.0
    DEL
    ```

