![[Pasted image 20240916083212.png]]

## Solve
```python
from pwn import xor

raw = '73626960647f6b206821204f21254f7d694f7624662065622127234f726927756d'
byte = bytes.fromhex(raw)

for i in range(256):
	flag = xor(byte, i)
	if b"crypto" in flag:
		print(flag.decode())
```

## Flag
crypto{0x10_15_my_f4v0ur173_by7e}