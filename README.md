## ENDPOINT OVERVIEW

| Name | Category | Status | Description |
| Summary Endpoint
(See sample) | Summary | Mandatory | Overview of market data for all tickers |
| Endpoint 1 
[(See sample)](asstes.md) | /asset | Recommended | In depth details on crypto currencies available on the exchange. |
| Endpoint 2
[(See sample)](ticker.md) | /ticker | Mandatory | 24-hour rolling window price change statistics for all markets. |
| Endpoint 3
[(See sample)](orderbook.md) | /orderbook | Mandatory | Market depth of a trading pair. One array containing a list of ask prices and another array containing bid prices. Query for level 2 order book with full depth available as minimum requirement. |
| Endpoint 4
[(See sample)](trades.md) | /trades | Mandatory | Recently completed trades for a given market. 24 hour historical full trades available as minimum requirement. |
