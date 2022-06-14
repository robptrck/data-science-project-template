# Project description
Accurately describe what it is, what it is trying to solve, and it's core ideas (the functionality). If possible, include examples of those.
<br>
<br>
<br>

# Video walkthrough
Insert video
<br>
<br>
<br>

# Full code here
Link to colab or sagemaker studio lab with reproducable work.
<br>
<br>
<br>

# Data Science Workflow
### Step 1: Ingest
Tools used: AWS S3, AWS Glue, AWS Athena
<br>
<br>

### Step 2: Clean & Transform
Tools used: AWS Athena, AWS SagemakerStudio
<br>
<br>

### Step 2: EDA (Exploratory Data Analysis)
Tools used: AWS Athena, AWS SageMaker Studio
<br>
<br>

### Step 3: Modeling (optional)
Tools used: AWS SageMaker Autopilot
<br>
<br>

### Step 4: Conclusion
Tools used: AWS Quicksight, Tableau
<br>
<br>
<br>

# Step 1: Ingest
Input here
<br>
<br>
<br>

# Step 2: Data Cleaning & Transformation
Check for:
* Correct data Types
* Missing Data
* Formatting issues
* Outliers
* Unique values 
  - (check for mispellings)
* Upstream issues (data collection, software bugs)
* Is the data of high quality? Are there bias in the data?
<br>
<br>
<br>

# Step 2: EDA
Input here
<br>
<br>
<br>

# Step 4: Modeling (optional)
Input here
<br>
<br>
<br>

# Step 5: Conclusion
Input here
<br>
<br>
<br>

# Resources:

```
# IMPORT

import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
%matplotlib inline
```

```
# READ .CSV TO PANDAS DATAFRAME (DF)

df = pd.read_csv('/user/folder/data_set.csv')
```

```
# DATA STRUCTURES

# LIST
list = ['1', '2', '3', 'a', 'b', 'c']



# DICTIONARY
dict = {'a': 199, 'b': 200, 'c', 201}

# DICTIONARY COMMAND
dict

# OUTPUT
{'1': a, 'b': 200, 'c':201}

# DICTIONARY COMMAND
dict['a']

# OUTPUT
a



# SERIES
s = pd.Series(np.random.randn(5), index=["a", "b", "c", "d", "e"])

# SERIES COMMAND
s

# SERIES OUTPUT
a    0.469112
b   -0.282863
c   -1.509059
d   -1.135632
e    1.212112



# DATAFRAME (DF)
# SIMILAR TO EXCEL TABLE
```

```
# EXPLORATORY DATA ANALYSIS

# DESCRIPTIVE STATISTICS
DataFrame.describe()


```

```
# SEABORN

# REQUIRED
pip install seaborn

import seaborn as sns
import matplotlib.pyplot as plt
%matplotlib inline

df = seaborn.load_dataset({file_name}.csv on https://github.com/username/repository-name)
```

# Try this in seaborn
```
sns.set()
sns.set_context("notebook", rc={"lines.linewidth": 1.5})
sns.set_style("whitegrid")

plt.xlabel("X LABEL", fontsize=16)
plt.ylabel("Y LABEL", fontsize=16)
plt.title("MY TITLE", fontsize=20)

sns.histplot(data=df, x="column_name", kde=True)
```

# Transform object to datetime

```
# convert timestamp from object to datetime

df['col_name'] = pd.to_datetime(df['col_name'])

df.dtypes
```
