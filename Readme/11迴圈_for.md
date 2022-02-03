# 11.迴圈_for
## for循環語句
python使用格式如下
```python
for 變數 in 範圍:
    #要做的事情
```
### Code
```python
#輸出1到10
i=0
for i in range(1, 11):  #range()等等會講解
    print (i)
```

## for...else循環語句
python使用格式如下
```python
for 變數 in 範圍:
    #要做的事情
else:
    #要做的事情
```
### Code
```python
#質數判斷
for num in range(10,20):    #反覆運算 10 到 20 之間的數字
    for i in range(2,num):  #根據因數反覆運算 
        if num%i == 0:      #確定第一個因數 
            j=num/i         #計算第二個因數 
            print ('%d 等於 %d * %d' % (num,i,j)) 
            break           #跳出當前迴圈 
    else:   #迴圈的 else 部分 
        print ('%d 是一個質數' % num)
```


## range()
>+ range() 是 for 陳述句常用的迭代範圍
>+ Code中的range(1, 11) 代表 1到10
>+ 11是代表到此為止的終點，不准越過，也不准涵蓋進去