# EXNO-6-DS-DATA VISUALIZATION USING SEABORN LIBRARY

# Aim:
  To Perform Data Visualization using seaborn python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```
import matplotlib.pyplot as plt
import seaborn as sns
x=[1,3,6,9,12,15]
y=[1,2,4,6,8,10]
sns.lineplot(x=x,y=y)
plt.show()
```


<img width="839" height="659" alt="Screenshot 2025-10-15 212919" src="https://github.com/user-attachments/assets/ab95c8ef-01f5-4f47-b273-663d24d9e9aa" />



```
import matplotlib.pyplot as plt
import seaborn as sns
x1=[1,2,3,4,5]
y1=[1,4,6,8,10]
x2=[2,4,6,8,0]
y2=[4,6,8,0,12]
sns.lineplot(x=x1,y=y1)
sns.lineplot(x=x2,y=y2)
plt.title("Multiline plot")
```

<img width="871" height="667" alt="Screenshot 2025-10-15 213005" src="https://github.com/user-attachments/assets/9851a651-c317-4535-bd80-fb756807394f" />


```
import seaborn as sns
import matplotlib.pyplot as plt
import pandas as pd

data = pd.DataFrame({
    'Category': ['A', 'B', 'C', 'D'],
    'Value': [10, 24, 36, 18]
})

sns.barplot(x='Category', y='Value', data=data)
plt.title('Basic Bar Plot')
plt.show()
```

<img width="931" height="708" alt="Screenshot 2025-10-15 213042" src="https://github.com/user-attachments/assets/077347ca-a255-45ec-83de-d4ce861b21b8" />


```
import seaborn as sns
import matplotlib.pyplot as plt
import pandas as pd

data = pd.DataFrame({
    'X': [5, 7, 8, 7, 2, 17, 2, 9],
    'Y': [99, 86, 87, 88, 100, 86, 103, 87]
})

sns.scatterplot(x='X', y='Y', data=data)
plt.title('Simple Scatter Plot')
plt.show()
```

<img width="1053" height="695" alt="Screenshot 2025-10-15 213111" src="https://github.com/user-attachments/assets/4a4be1d6-04e1-4c3d-86a2-df8042109bfc" />


```
import seaborn as sns
import matplotlib.pyplot as plt
import pandas as pd
data = [5, 7, 8, 7, 2, 17, 2, 9, 4, 11, 12, 9, 6]

sns.histplot(data, bins=5, kde=False)
plt.title('Simple Histogram')
plt.show()
```


<img width="964" height="682" alt="Screenshot 2025-10-15 213141" src="https://github.com/user-attachments/assets/b044ea4a-1480-4cfa-a344-e5e4361fb10c" />


```
import seaborn as sns
import matplotlib.pyplot as plt
import pandas as pd

data = pd.DataFrame({
    'Category': ['A', 'A', 'A', 'B', 'B', 'B', 'C', 'C', 'C'],
    'Value': [10, 12, 14, 20, 22, 19, 30, 28, 35]
})

sns.boxplot(x='Category', y='Value', data=data)
plt.title('Box Plot')
plt.show()
```

<img width="901" height="711" alt="Screenshot 2025-10-15 213218" src="https://github.com/user-attachments/assets/0cb62f45-0e5e-418d-89ff-f61214e1c15d" />


```
import seaborn as sns
import matplotlib.pyplot as plt

data = [5, 7, 8, 7, 2, 17, 2, 9, 4, 11, 12, 9, 6]

sns.kdeplot(data)
plt.title('Simple KDE Plot')
plt.show()
```

<img width="930" height="676" alt="Screenshot 2025-10-15 213251" src="https://github.com/user-attachments/assets/3b7177e0-e4fe-4a82-8939-b0882d53199a" />


```
import seaborn as sns
import matplotlib.pyplot as plt
import numpy as np

data = np.array([[1, 2, 3],
                 [4, 5, 6],
                 [7, 8, 9]])

sns.heatmap(data, annot=True, cmap='Blues')
plt.title('Simple Heatmap')
plt.show()
```

<img width="835" height="681" alt="Screenshot 2025-10-15 213328" src="https://github.com/user-attachments/assets/c5d6a116-6fa8-4e6a-8938-10737a9b732e" />


# Result:

 Seaborn offers high-level functions like sns.lineplot(), sns.barplot(), sns.histplot(), sns.boxplot(), sns.heatmap(), and sns.scatterplot() to create beautiful, statistical visualizations with minimal code.

