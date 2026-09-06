---
title: Determinant in numpy
template: default
---

We can calculate this in numpy

```python
A_1=np.array([1,-1,1])
A_2=np.array([1,1,0])
A_3=np.array([1,-1,-1])
A=np.column_stack((A_1,A_2,A_3))
print(np.linalg.det(A))
# -4
```

