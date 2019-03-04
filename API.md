# Documentation for the API of https://flame.exchange


## The Public API



### Ticker:
https://flame.exchange/api/1/ticker

Example Output:
```
[{"first":"0.00000100","low":"0.000001","high":"0.0003","last":"0.00030000","volume":"26.392","base":"EZY","counter":"BTC"}]
```


### Chart:

https://flame.exchange/api/1/chart/BASE/COUNTER

Example Output: (Fetched from /EZY/BTC)
```
[[1547287200000,0.000001,0.0001,0.000001,0.0001,2.1],[1547319600000,0.00001,0.0003,0.00001,0.0003,24.292]]
```
