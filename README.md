# Read CSV file from online

```import pandas as pd```

```import requests```

```url = 'https://raw.githubusercontent.com/jarif87/DataSets/main/pokemon.csv'```

```response = requests.get(url)```

```data = pd.read_csv(url)```

```data.head()```
