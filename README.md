### Atcoder Memo

配列を2倍にする

```python
list = [1,2,3]
new1 = [n*2 for n in list]
print(new1) # 2,4,6
```

配列から重複除外

```python
list = [1,2,3]
print(list(set(l)))
```

for文の組み合えわせ

```python
for i in range(x):
    for k in range(x):
```

- リストから3つをチョイス
```python
for a, b, c in combinations(li, 3):
```

- 各桁の合計を求める
```python
n = 123
result = sum(list(map(int, str(n))))
```

- 各桁を配列にして表現
```python
i = 123
result = list(map(int, str(i)))
```

- 浮動小数点数の演算は一般に誤差を含む
```python
good : i * 0.01
bad  : k * 100
```
