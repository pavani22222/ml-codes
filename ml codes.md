```python
import numpy as np
array1 = np.array([[1, 2, 3],
                   [4, 5, 6]])
array2 = np.array([[7, 8, 9],
                   [10, 11, 12]])
result_array = array1 * array2

print("Array 1:")
print(array1)

print("Array 2:")
print(array2)

print("Result of element-wise multiplication:")
print(result_array)

```

    Array 1:
    [[1 2 3]
     [4 5 6]]
    Array 2:
    [[ 7  8  9]
     [10 11 12]]
    Result of element-wise multiplication:
    [[ 7 16 27]
     [40 55 72]]
    


```python
import numpy as np
data = np.array([1, 2, np.nan, 4, np.nan, 6, 7, np.nan])
missing_indices = np.isnan(data)
num_missing = np.sum(missing_indices)
print("Original Array:", data)
print("Indices of Missing Data:", missing_indices)
print("Number of Missing Values:", num_missing)

```

    Original Array: [ 1.  2. nan  4. nan  6.  7. nan]
    Indices of Missing Data: [False False  True False  True False False  True]
    Number of Missing Values: 3
    


```python
import numpy as np
array1 = np.array([1, 2, 3, 4, 5])
array2 = np.array([3, 4, 7, 8, 9])
presence_test = np.in1d(array1, array2)
print("Array 1:", array1)
print("Array 2:", array2)
print("Presence of elements from array1 in array2:", presence_test)
```

    Array 1: [1 2 3 4 5]
    Array 2: [3 4 7 8 9]
    Presence of elements from array1 in array2: [False False  True  True False]
    


```python
import numpy as np
data = np.array([[1, 2, 3],
                 [4, 5, 6],
                 [7, 8, 9]])
file_path = 'sample_array.txt'
np.savetxt(file_path, data, fmt='%d', delimiter=',')
print("Array saved successfully to", file_path)
```

    Array saved successfully to sample_array.txt
    


```python
import numpy as np
array = np.linspace(2.5, 6.5, 30)
print("1-D array of 30 evenly spaced elements between 2.5 and 6.5:")
print(array)

```

    1-D array of 30 evenly spaced elements between 2.5 and 6.5:
    [2.5        2.63793103 2.77586207 2.9137931  3.05172414 3.18965517
     3.32758621 3.46551724 3.60344828 3.74137931 3.87931034 4.01724138
     4.15517241 4.29310345 4.43103448 4.56896552 4.70689655 4.84482759
     4.98275862 5.12068966 5.25862069 5.39655172 5.53448276 5.67241379
     5.81034483 5.94827586 6.0862069  6.22413793 6.36206897 6.5       ]
    


```python

```
