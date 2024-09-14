![[Pasted image 20240915063145.png]]

## Solve
```python
raw = '63727970746f7b596f755f77696c6c5f62655f776f726b696e675f776974685f6865785f737472696e67735f615f6c6f747d'
flag = bytes.fromhex(raw)

print(flag.decode())
```

## Flag
crypto{You_will_be_working_with_hex_strings_a_lot}