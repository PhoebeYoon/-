### 숫자 알아맞추기.  

#### :pencil: vscode 실행 -> 파일저장 (확장자:*.py) -> 실행메뉴 > 디버그 시작  

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
