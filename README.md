# Boston-Dataset-in-Sklearn
Boston Dataset in Sklearn
I got to know that the file is no longer usable with the given following code
so i downloaded the csv file  directly and used that localy to 
1. Apply a Linear Regression Model to this data
2. Evaluate the model using Mean Squared Error
the ipynb file that is provided here has the the following output

![output](https://github.com/user-attachments/assets/6f747065-3f46-4f7a-b88d-681f84f90da1)

```code
import pandas as pd
from sklearn.datasets import load_boston
# Load the dataset
boston = load_boston()
df = pd.DataFrame(boston.data, columns=boston.feature_names)
# Display the DataFrame
print(df)
