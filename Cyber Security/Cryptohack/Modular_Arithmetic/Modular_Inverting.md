![[Pasted image 20240916080853.png]]

## Note
Fermat's Litle Theorem
````python
a^(p-1) ≡ 1 mod p <=> a^(p-1) % p = 1
````

## Solve
I don't understand what that mean
```python
a^(p-1) ≡ 1 mod p
a^(p-1) * a^(-1) ≡ a^(-1) mod p
a^(p-2) * a * a^(-1) ≡ a^(-1) mod p
a^(p-2) ≡ a^(-1) mod p 
<=>
a^(p-2) % p = a^(-1)

3 * d ≡ 1 mod 13

3^(13-2) % 13 = 9
```

but, this more simple to use
```python
from Crypto.Util.number import inverse

print(inverse(3, 13))
```

## Flag
9