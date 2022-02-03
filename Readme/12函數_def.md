# 12.函數
> 這就是PHP的 function

python使用格式如下
```
def 函數名():
```


### Code
```python
def func():
    print("我是func")   #輸出

def func01(a):
    a+=20               #a = a + 20
    return a            #回傳 以便後面利用

func()                  #執行def func():
print (func01(10) + 10) #輸出變執行def func01(a):
```
### OUTPUT
```
我是func
40
```