# 本周学习
### 1. [SWPUCTF 2021 新生赛] crypto2

```python
from gmpy2 import *
from Crypto.Util.number import *

flag = '***************'

p = getPrime(512)
q = getPrime(512)
m1 = bytes_to_long(bytes(flag.encode()))

n = p * q
e1 = getPrime(32)
e2 = getPrime(32)

flag1 = pow(m1, e1, n)
flag2 = pow(m1, e2, n)
print('flag1= ' + str(flag1))
print('flag2= ' + str(flag2))
print('e1= ' + str(e1))
print('e2= ' + str(e2))
print('n= ' + str(n))
```
