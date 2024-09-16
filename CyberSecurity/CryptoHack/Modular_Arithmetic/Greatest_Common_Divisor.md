![[Pasted image 20240916070002.png]]

## Solve
```python
def gcd(a, b):
	if b == 0:
		return a
	else:
		return gcd(b, a % b)

print(gcd(66528, 52920))
```

## Flag
1512