# 12.函數
> 這就是PHP的 function

python使用格式如下
##無參數傳入
```
def 函數名():
    print("i like panda")
```
##有參數傳入
```
def 函數名(x):              #只傳入一個參數
    print("你傳入:",x)

def 函數名(a, b, c):        #傳入多個參數
    num=a+b+c
    print(num)
```

### Code
```python
def func():
    print("我是func")        #輸出

def func01(a):
    a+=20                   #a = a + 20
    return a                #回傳 以便後面利用
    
def func02(a, b, c):        #傳入多個參數
    num=a+b+c
    print(num)

func()                      #執行def func():
func02(1,2,3)               #執行def func02(a, b, c):
print (func01(10) + 10) #輸出變執行def func01(a):
```
### OUTPUT
```
我是func
40
6
```
