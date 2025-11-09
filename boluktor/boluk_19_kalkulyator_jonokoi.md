# Бөлүк 19: Жөнөкөй калькулятор

```python
a = float(input("a: "))
b = float(input("b: "))
belgi = input("Белги (+, -, *, /): ")

if belgi == "+":
    print(a + b)
elif belgi == "-":
    print(a - b)
elif belgi == "*":
    print(a * b)
elif belgi == "/":
    if b != 0:
        print(a / b)
    else:
        print("Нөлгө бөлүү болбойт!")
else:
    print("Белги түшүнүксүз.")
```

**Тапшырма:** Даража (`**`) кошуңуз.
