### sin(x) 함수 그리기
```python
import numpy as np
%matplotlib inline
import matplotlib.pyplot as plt
x=np.linspace(-5,5,100)
y=np.sin(x)
plt.plot(x,y)
```

### cos(x)를 그리는 함수
`y=np.sin(x)`