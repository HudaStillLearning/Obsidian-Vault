![[Pasted image 20240915062421.png]]

## Solve
```python
raw = [99, 114, 121, 112, 116, 111, 123, 65, 83, 67, 73, 73, 95, 112, 114, 49, 110, 116, 52, 98, 108, 51, 125]
flag = ''

for i in raw:
	flag += chr(i)

print(flag)
```

## Flag
crypto{ASCII_pr1nt4bl3}