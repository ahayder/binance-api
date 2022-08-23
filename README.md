# Binance APIs List

## Binance Price APIs Sample Call & Response

### Get the price for a pair
```url
https://api.binance.com/api/v3/ticker/price?symbol=MATICUSDT
```
```json
{
"symbol": "MATICUSDT",
"price": "0.82180000"
}
```

### Get the price change for last 24 hours
```url
https://api.binance.com/api/v3/ticker/24hr?symbol=MATICUSDT
```
```json
{
"symbol": "MATICUSDT",
"priceChange": "0.03590000",
"priceChangePercent": "4.553",
"weightedAvgPrice": "0.80777306",
"prevClosePrice": "0.78850000",
"lastPrice": "0.82440000",
"lastQty": "727.80000000",
"bidPrice": "0.82450000",
"bidQty": "1915.00000000",
"askPrice": "0.82460000",
"askQty": "1065.70000000",
"openPrice": "0.78850000",
"highPrice": "0.82950000",
"lowPrice": "0.78000000",
"volume": "63738789.50000000",
"quoteVolume": "51486477.16460000",
"openTime": 1661182089887,
"closeTime": 1661268489887,
"firstId": 278640985,
"lastId": 278819758,
"count": 178774
}
```
