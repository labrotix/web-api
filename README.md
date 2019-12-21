
Wrapper for labrotix.com Api

## Issue reporting
Feel free to report any bugs/issues you may find in the framework. It's all much appreciated!

## Quick Start

Public HTTP API Methods`


There are seven public methods, all of which take HTTP GET requests and return output in JSON format. No authentication is necessary but you must not excessively use any API endpoint.

returnTicker
```
Example 1. Return of all tickers.

Request: https://www.labrotix.com/public/v1/ticker

Response:

{"BTC_LTC":{"id":00,"last":"0.00000000","lowestAsk":"0.00000000","highestBid":"0.00000000","percentChange":"0.00","baseVolume":"0.00000000","quoteVolume":"0.00000000","isFrozen":"0","high24hr":"0.00000000","low24hr":"0.00000000"}}

Response:

{"BTC_XXX":{"id":00,"last":"0.00000000","lowestAsk":"0.00000000","highestBid":"0.00000000","percentChange":"0.00","baseVolume":"0.00000000","quoteVolume":"0.00000000","isFrozen":"0","high24hr":"0.00000000","low24hr":"0.00000000"}}

 

Example 2. Return of BTC_LTC and  tickers.

Request: https://www.labrotix.com/public/v1/ticker/BTC_LTC

 

Response:

{"BTC_LTC":{"id":00,"last":"0.00000000","lowestAsk":"0.00000000","highestBid":"0.00000000","percentChange":"0.00","baseVolume":"0.00000000","quoteVolume":"0.00000000","isFrozen":"0","high24hr":"0.00000000","low24hr":"0.00000000"}}
```


## Other
-
https://www.labrotix.com/api
-
info@labrotix.com
-
https://discord.gg/Ek4Z5sJ
