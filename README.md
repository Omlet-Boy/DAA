# DAA Notes

Write a Python Program Using a recursive function to calculate the sum of a sequence

![image](https://user-images.githubusercontent.com/102067946/198812335-8ea99c24-fc40-4094-8592-d97e72ab3e35.png)

```py
a = int(input())

def sumNum(num):
    if num == 0:
        return num
    else:
        return num + sumNum(num-1)

print(sumNum(a))
```
