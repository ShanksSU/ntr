# 11.迴圈_for
> range()是for迴圈指定範圍最常用的函數
## range()
>+ range() 是 for 陳述句常用的迭代範圍
>+ Code中的range(1, 11, 2) 代表 從1到10間隔為2, 如果沒寫預設為1
>+ 11是代表到此為止的終點，不准越過，也不准涵蓋進去

## for循環語句
python使用格式如下
```python
for 變數 in 範圍:
    #要做的事情
```
### Code_讀取range()_1
```python
#輸出1,3,5,7,9
for i in range(1, 11, 2):  #range(初始值, 終點值, 間隔值)
    print (i)
```
### Code_讀取range()_2
```python
#輸出1到10
for i in range(1, 11):  #range(初始值, 終點值) 間隔值沒有寫預設就是1
    print (i)
```
### Code_讀取陣列(列表)
```python
#輸出列表的每一項值
arr=['runoob', 786, 2.23, 'john', 70.2]
for i in arr:
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
