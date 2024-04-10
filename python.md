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
