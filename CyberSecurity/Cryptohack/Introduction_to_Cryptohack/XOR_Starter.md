![[Pasted image 20240916083126.png]]

## Solve
```python
from pwn import xor

flag = xor(b'label', 13).decode()

print('crypto{'+ flag + '}')
```

## Flag
crypto{aloha}