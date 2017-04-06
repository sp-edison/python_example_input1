# python_example_input1

EDISON 시뮬레이션 SW 개발자를 위한 1개의 입력 파일 읽는 Python 예제 파일입니다.

본 예제는 ./[실행파일명] -[옵션] [입력 파일 경로]로 실행시 옵션 뒤에 입력된 경로의 파일을 열고 닫는 예제로 ```main.py``` 파일 하나로만 구성되어 있습니다.

- EDISON 플랫폼에 업로드시 별도 컴파일 과정은 필요 없습니다. 따라서 실행 파일 업로드 하는 부분에 python 코드만 압축하여 업로드 하면 됩니다.
- 실행파일이 실행되는 과정에서 $PATH, $LD_LIBRARY_PATH 등의 환경변수 등록이 필요한 경우 실행파일과 같은 폴더 안에 **simrc**라는 파일을 만들어 해당 변수들을 추가해야 합니다. 
- 결과 파일은 실행 파일이 있는 경로에 result 폴더를 생성해야 합니다.

```python 
    os.system("rm -rf result")
    os.system("mkdir result")
```
