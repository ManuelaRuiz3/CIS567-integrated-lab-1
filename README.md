# CIS567-integrated-lab-1
Repository for zyBooks Integrated Lab 1 - CIS567

```python
first = int(input())
second = int(input())

if second < first:
    print("Second integer can't be less than the first.")
else:
    value = first
    while value <= second:
        print(value, end=' ')
        value += 5
    print()
```
