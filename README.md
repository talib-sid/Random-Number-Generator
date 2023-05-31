# Random-Number-Generator

We have created a Random Number Generator with the function

```python
def gen_random_func(N):
    I = np.zeros(N,dtype=np.uint32)
    I[0] = 1
    for i in range (1,N):
        I[i] = (A * I[i-1] + C) % M
    return I
```


We have initialised the variables as:
```python
N = 1000
A = 106
C = 1283
M = 6075
```


To instill a higher degree of randomness, you could even keep these variables as randomly generated within a suitable range!!
