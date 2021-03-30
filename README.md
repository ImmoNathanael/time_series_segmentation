# Time series segmentation
> Univariate and multivariate time series segmentation. Including example data sets.


This file will become your README and also the index of your documentation.

## How to use

Fill me in please! Don't forget code examples:

```python
df_train, df_test, df_sample = get_liverpool_ion_data()
```

    data folder already exists
    

```python
df_train.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>time</th>
      <th>signal</th>
      <th>open_channels</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>0.0001</td>
      <td>-2.7600</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>0.0002</td>
      <td>-2.8557</td>
      <td>0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>0.0003</td>
      <td>-2.4074</td>
      <td>0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>0.0004</td>
      <td>-3.1404</td>
      <td>0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>0.0005</td>
      <td>-3.1525</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
</div>



```python
train_train, train_val = dataframe_split(df_train, fraction = 0.1, random_state = 42, sep_col='seq_idx')
```
