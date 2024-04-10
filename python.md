##python dictionary
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
