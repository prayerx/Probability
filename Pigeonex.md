
# Güvercin Yuvası Örneği

## Aynı ayda doğanlar

N sayıda kişinin katıldığı bir partide en az $\lfloor N/12 \rfloor = 1 $ kişi başka bir kişiyle aynı ayda doğmuş olmalıdır. Bunu bir örnek üzerinden açıklayalım.

13 kişinin katıldığı bir partide en az 1 kişi başka bir kişiyle aynı ayda doğmuş olmalıdır. Bu önermeyi güvercin yuvası prensibine uyarlamak istediğimizde insanlar güvercin, aylar ise yuva olacaktır.
Güvercin/Yuva işlemini uyguladığımızda önermenin doğru olduğunu görmekteyiz.

$\lfloor 13/12 \rfloor = 1 $



```python
import math

people = 13
months = 12

control = (people/months) - 0.01

print("Partideki en az", math.floor(control), "kişi başka bir kişiyle aynı ayda doğmuş olmalıdır.")
```

    Partideki en az 1 kişi başka bir kişiyle aynı ayda doğmuş olmalıdır.


Enes Yıldırım 185112053
