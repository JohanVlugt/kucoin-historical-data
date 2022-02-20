# Kucoin historical data
ohlcv history of 300+ Kucoin pairs

Below you can find the historical data uploaded to the cloud.

The data is separated in 2 zipped files containing: ```1m``` and ```5m 15m 30m 1h 2h 4h 6h 8h 12h 1d 1w``` data.

```1m``` data:

Link1                             

```5m 15m 30m 1h 2h 4h 6h 8h 12h 1d 1w``` data:

Link 2



## Maintaining downloaded data

You can maintain the data yourself by using the `docker-compose` file.
You will need the provided ```config.json``` to connect to the kucoin-proxy.

## Credits

Proxy used to download data: https://github.com/mikekonan/exchange-proxy

Framework used to convert data to json: https://github.com/freqtrade/freqtrade
