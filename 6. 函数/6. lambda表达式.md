```python
pairs = [[1, "one"], [2, "two"], [3, "three"], [4, "four"]]

pairs.sort(key=lambda pair: pair[1])  # 每个元素使用第二个变量比较大小
print(pairs)  # 输出：[[4, 'four'], [1, 'one'], [3, 'three'], [2, 'two']]
```
