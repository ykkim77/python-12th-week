# 모듈


## mod1.py

```
def add(a,b):
    return a+b

def sub(a,b):
    return a-b
#if __name__ == "__main__":
print('mod1이 실행되었습니다.')
```

## mod2.py

```
import math

class Circle():
    def calculate_circle_area(self,radius):
        if radius < 0:
            return "반지름은 음수가 될 수 없습니다."
        else:
            area = math.pi * radius ** 2
            return area
```

## mod3.py

```
def mul(a,b):
    return a*b
```