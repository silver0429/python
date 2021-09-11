### 本周学习目标 ###

#### 1.课本代码(项目一，从奇数中选择对应的时间节点)


```python
# 从pythin基础库中找到datetime模块

from datetime import datetime

```


```python
datetime.today().minute
```




    26




```python
# 课本代码(项目一，从奇数中选择对应的时间节点)

odds = [1,3,5,7,9,11,13,15,17,19,21,23,25,27,29,31,33,35,37,39,41,43,45,47,49,51,53,55,57,59]

right_this_minute = datetime.today().minute

if right_this_minute in odds:
    print("时间是奇数，时间在odds的数据中")
else:
    print("Not an odd minute.")
    
    
```

    Not an odd minute.
    

#### 2.认识变量


```python
2+2
```




    4




```python
 17 / 3  # classic division returns a float
```




    5.666666666666667




```python
 'spam eggs'  # single quotes
```




    'spam eggs'




```python
 'doesn\'t'  # use \' to escape the single quote...
```




    "doesn't"




```python
"doesnt't"
```




    "doesnt't"




```python
age_a = 20
```


```python
age_a + 1
```




    21




```python
type(age_a)
```




    int




```python
age_b = "20"
```


```python
type(age_b)
```




    str




```python
age_b + 1
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-26-ea718141ff43> in <module>
    ----> 1 age_b + 1
    

    TypeError: can only concatenate str (not "int") to str


#### 3.if else


```python
if today == "Saturday":
    print("Party!")
elif today == "Sunday":
    if condition == "Headache":
        print("Recover, then rest.")
    else:
        print("Rest.")
else:
    print("Work, work, work.")
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    <ipython-input-38-9c4a2e374030> in <module>
    ----> 1 if today == "Saturday":
          2     print("Party!")
          3 elif today == "Sunday":
          4     if condition == "Headache":
          5         print("Recover, then rest.")
    

    NameError: name 'today' is not defined



```python

```
