```

import numpy as np
import pandas as pd

data = np.array([[5.8, 0.8,3, 9]])
data2 = np.array([[9.0, 2.2,7, 0]]) 


dataset = pd.DataFrame({'x': data[0, :], 'y': data2[0, :]})


dataset.corr(method='pearson')

```
