## 알아야할 기초지식: 

1. 파이썬 인터프리터 
2. 숫자, 문자, 리스트
3. 제어문: if문, for문, range() 함수
4. 키워드
5. 입력문과 출력문

## 참조사이트 :  
https://wiki.python.org/moin/GameProgrammingBooks

### 숫자 알아맞추기  (예를들어 )
``` python
import random
num = random.randint(1, 100)
while True:
  print('숫자를 추측해보세요')
  guess=input()
  i = int(guess)
  if i==num:
    print("You gessed right")
  elif i<num:
    print("try higher")
  elif i>num:
    print('Try Lower')
```
#### :pencil: vscode 실행 -> 파일저장 (확장자:*.py) -> 실행메뉴 > 디버그 시작  
