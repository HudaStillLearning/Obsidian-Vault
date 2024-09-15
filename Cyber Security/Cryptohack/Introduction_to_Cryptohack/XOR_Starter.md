![[/Assets/CryptoHack/Introduction_to_Cryptohack/Pasted image 20240915071023.png]]

## Solve
```python
from pwn import xor

flag = xor(b'label', 13).decode()

print('crypto{'+ flag + '}')
```

## Flag
crypto{aloha}