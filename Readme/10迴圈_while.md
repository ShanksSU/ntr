# 10.迴圈_while
## while循環語句
python使用格式如下
```python
while 判斷條件:             #注意 冒號
    #要做的事情             #注意 縮排(Tab鍵)
```
### Code
```python
#輸出0到10
count = 0
while (count <= 10):
   print (count)
   count = count + 1
```

## while...else循環語句
python使用格式如下
```python
while 判斷條件:             #注意 冒號
    #成立時要做的事情             #注意 縮排(Tab鍵)
else:
    #不成立時要做的事情
```
### Code
```python
count = 100
while (count <= 10):
    print (count)
    count = count + 1

    if count == 6:      #如果count等於6就跳出迴圈
        break
else:
    print ("chi")
```

## 跳出迴圈
python使用格式如下
```python
while 判斷條件:             #注意 冒號
    #要做的事情             #注意 縮排(Tab鍵)
    ....

    if 判斷條件:            #如果成立
        break              #跳出迴圈
```

### Code
```python
#輸出0到10
count = 0
while (count <= 10):
    print (count)
    count = count + 1

    if count == 6:      #如果count等於6就跳出迴圈
        break
```