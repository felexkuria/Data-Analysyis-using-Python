# Pandas DataFrame Example

A simple example demonstrating basic Pandas DataFrame operations in Python.

## Overview

This code shows how to:

- Create a DataFrame from a dictionary
- Display DataFrame contents
- Access and filter DataFrame data

## Code Description

The code creates a DataFrame with:

- 3 columns: Name, Age, Score
- 3 rows of sample data
- Basic filtering example showing scores above 90

## Requirements

- Python 3.x
- Pandas library (`pip install pandas`)

## Usage

```python
import pandas as pd

# Create sample data
data = {
    'Name': ['Alice', 'Bob', 'Charlie'],
    'Age': [24, 30, 22],
    'Score': [85, 90, 95]
}

# Create DataFrame
df = pd.DataFrame(data)

# Display full DataFrame
print(df)

# Filter for scores > 90
filtered_df = df[df['Score'] > 90]
print(filtered_df)
arkdown
# Pandas DataFrame Example

A simple example demonstrating basic Pandas DataFrame operations in Python.

## Overview

This code shows how to:
- Create a DataFrame from a dictionary
- Display DataFrame contents
- Access and filter DataFrame data

## Code Description

The code creates a DataFrame with:
- 3 columns: Name, Age, Score
- 3 rows of sample data
- Basic filtering example showing scores above 90

## Requirements

- Python 3.x
- Pandas library (`pip install pandas`)

```
