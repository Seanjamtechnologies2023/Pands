# Pands
```python import pandas as pd  file_path = 'your_file.csv' df = pd.read_csv(file_path) df['column_to_change'] = df['column_to_change'].apply(lambda x: x * 2) df.to_csv(file_path, index=False) ```
