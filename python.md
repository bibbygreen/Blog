##python dictionary
>建立字典
```
heights = dict(Mike=170, Peter=165)
print(heights)
//{"Mike": 170, "Peter": 165}
```


> 新增元素
```
heights = {"Mike": 170, "Peter": 165}
heights["John"] = 175

//{{"Mike": 170, "Peter": 165, John: 175}
```

> 迴圈讀取字典，同時存取key和value
```
heights = {"Mike": 170, "Peter": 165}
for height in heights.items():
    print(height)

// 回傳Tuple
("Mike", 170)
("Peter", 165)

```
> get() 傳入要尋找的key，回傳其value
```
heights = {"Mike": 170, "Peter": 165}
print(heights.get("Peter")
//165

print(heights.get("Bob")
//None
```

> append(), extend()
```
time = [9, 10 ,11]
time.extend([12, 13])

print(time)
//[9, 10, 11, 12, 13]


time2 = [9, 10 ,11]
time2.append([12, 13])

print(time2)
//[9, 10, 11, [12, 13]]
```
## 使用keys()、values()、items()來取得所有的鍵、值、項目
>使用keys()方法取得所有的鍵(key)
```
afternoon_tea = {'Muffin': 39, 'Scone': 25, 'Biscuit': 20}
afternoon_tea.keys()
//dict_keys(['Muffin', 'Scone', 'Biscuit'])

list(afternoon_tea.keys())
['Muffin', 'Scone', 'Biscuit']
```
>使用values()方法取得所有的值(value)
```
list(afternoon_tea.values())
[39, 25, 20]
```

>使用items()方法取得所有的項目(item)
取得所有的項目，並回傳串列這個資料型態
```
list(afternoon_tea.items())
[('Muffin', 39), ('Scone', 25), ('Biscuit', 20)]
```

>使用zip()函式建立字典
```
>>> name = ['Muffin', 'Scone', 'Biscuit']
>>> price = [39, 25, 20]
>>> dict(zip(name, price))
// {'Muffin': 39, 'Scone': 25, 'Biscuit': 20}
```

>使用生成式(dict comprehensions)建立字典
```
>>> {x: x**2 for x in range(1, 4}
{1: 1, 2: 4, 3: 9}
```
