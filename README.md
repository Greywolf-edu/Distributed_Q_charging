# Wireless Rechargable Sensors Network
## Distributed Q_charging

- Implementation of a distributed Q_learning-based charging strategy with Kmeans net-partition on WRSN with multiple Mobile Chargers.



## Experiments:


```bash
$ python Test.py
experiment_type:
experiment_index:
```

| Experiment_index Experiment_type | 0   | 1   | 2     | 3   | 4   | 5     | 6     | 7   | 8   |
|------------------                |-----|-----|-----  |-----|-----|-----  |-----  |-----|-----|
| node                             |`300`|`350`|__400__|`450`|`500`| 550   | 600   | 650 | 700 |
| target                           |`200`|`250`|__300__|`350`|`400`| 450   | 500   | 550 | 600 |
| MC                               | 1   |`2`  |__3__  | `4` |`5`  |`6`    | 7     | 8   | 9   |
| prob                             | 0.1 | 0.2 | 0.3   |`0.4`|`0.5`|__0.6__|`0.7`  |`0.8`| 0.9 |
| package                          | 400 | 450 | 500   | 550 |`600`|`650`  |__700__|`750`|`800`|


> `target` experiments must be *reconstructed* to match `node` experiments range if modified 
## Results:

- All expriment results are updated at this [sheet](https://husteduvn-my.sharepoint.com/:x:/g/personal/long_nt183586_sis_hust_edu_vn/EVypWNIGoz1GkK7v6QYDmccBJKAzweAXJr8ZhFF94kYgnw?e=Jrwb9k).

## Requirements:
- `pandas==1.1.3`  
- `scipy==1.5.2`    
- `numpy==1.19.2`
- `scikit_learn==0.24.2`
