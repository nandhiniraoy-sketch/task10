# 📘 Task 10: NumPy Indexing and Slicing

## Objective

Learn NumPy indexing and slicing using 1D and 2D arrays.

## Requirements

-   1D indexing examples
-   2D indexing examples
-   Five slicing examples
-   Zero-based indexing explanation

## Code

``` python
import numpy as np

arr=np.array([10,20,30,40,50])
print(arr[0])
print(arr[2])
print(arr[-1])

arr=np.array([[1,2,3],[4,5,6],[7,8,9]])
print(arr[0,1])
print(arr[1,2])
print(arr[2,0])

arr=np.array([10,20,30,40,50,60])
print(arr[1:4])
print(arr[:3])
print(arr[2:])
print(arr[-3:])
print(arr[::2])

arr=np.array([[1,2,3],[4,5,6],[7,8,9]])
print(arr[:,1])
print(arr[1,:])
```

## Output

    10
    30
    50
    2
    6
    7
    [20 30 40]
    [10 20 30]
    [30 40 50 60]
    [40 50 60]
    [10 30 50]
    [2 5 8]
    [4 5 6]

## Conclusion

Successfully learned NumPy indexing, slicing, and zero-based indexing.
