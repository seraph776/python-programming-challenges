# 100 + Python Programming Challenges

### Question 1
> Write a program which will find all such numbers which are divisible by 7 but are not a multiple of 5,
between 2000 and 3200 (both included). The numbers obtained should be printed in a comma-separated sequence on a single line.

### Solution

```python
def solve():
    return ", ".join([str(n) for n in range(2000, 3201) if n % 7 == 0 and n % 5 == 1])
```
### Output

```
2016, 2051, 2086, 2121, 2156, 2191, 2226, 2261, 2296, 2331, 2366, 2401, 2436, 2471, 2506, 2541, 2576, 2611, 2646, 2681, 2716, 2751, 2786, 2821, 2856, 2891, 2926, 2961, 2996, 3031, 3066, 3101, 3136, 3171
```
