![[Pasted image 20240916083057.png]]

## Solve
```python
from Crypto.Util.number import *

raw = 11515195063862318899931685488813747395775516287289682636499965282714637259206269
flag = long_to_bytes(raw).decode()

print(flag)
```

## Flag
crypto{3nc0d1n6_4ll_7h3_w4y_d0wn}