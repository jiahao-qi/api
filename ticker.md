## ticker

### Summary：

```The ticker endpoint is to provide a 24-hour pricing and volume summary for each market pair available on the exchange.```

### Request URL：

```https://open.loex.io/open/v1/ticker```

### Request：

```
GET
```

### Command:

```
curl -X GET https://open.loex.io/open/v1/ticker
```

### Request frequency：

```
5 times/1s
```
### Response Sample
```
{
	"ETC_LCNY": {
		"base_id": "54",
		"quote_volume": "8191548.42316000",
		"base_volume": "124415.12300000",
		"quote_id": "62",
		"isFrozen": "0",
		"last_price": "63.16000000"
	},
	"OMG_USDT": {
		"base_id": "87",
		"quote_volume": "4500420.09504460",
		"base_volume": "3902358.10000000",
		"quote_id": "49",
		"isFrozen": "0",
		"last_price": "1.10250000"
	},
	"XRP_LCNY": {
		"base_id": "63",
		"quote_volume": "155165617.84932200",
		"base_volume": "75691629.47000000",
		"quote_id": "62",
		"isFrozen": "0",
		"last_price": "1.96580000"
	},
	"PAX_USDT": {
		"base_id": "89",
		"quote_volume": "5371833.61461040",
		"base_volume": "5379422.33700000",
		"quote_id": "49",
		"isFrozen": "0",
		"last_price": "1.00060000"
	},
	"EOS_USDT": {
		"base_id": "66",
		"quote_volume": "2040942.88991097",
		"base_volume": "476691.18406083",
		"quote_id": "49",
		"isFrozen": "0",
		"last_price": "4.02600000"
	},
	"ETH_USDT": {
		"base_id": "51",
		"quote_volume": "38069983.27417769",
		"base_volume": "140487.08012046",
		"quote_id": "49",
		"isFrozen": "0",
		"last_price": "259.26000000"
	},
	"ICX_USDT": {
		"base_id": "95",
		"quote_volume": "750063.90374307",
		"base_volume": "1901794.67020000",
		"quote_id": "49",
		"isFrozen": "0",
		"last_price": "0.35220000"
	},
	"LRC_BTC": {
		"base_id": "86",
		"quote_volume": "34.05522089",
		"base_volume": "8455056.22910000",
		"quote_id": "50",
		"isFrozen": "0",
		"last_price": "0.00000437"
	},
	"ICX_BTC": {
		"base_id": "95",
		"quote_volume": "31.99492008",
		"base_volume": "805911.60300000",
		"quote_id": "50",
		"isFrozen": "0",
		"last_price": "0.00003685"
	},
	"BCH_LCNY": {
		"base_id": "53",
		"quote_volume": "245140678.57846400",
		"base_volume": "87464.80430000",
		"quote_id": "62",
		"isFrozen": "0",
		"last_price": "2704.26000000"
	},
	"LTC_LCNY": {
		"base_id": "52",
		"quote_volume": "26778368.89713000",
		"base_volume": "50561.09200000",
		"quote_id": "62",
		"isFrozen": "0",
		"last_price": "499.79000000"
	},
	"PAX_BTC": {
		"base_id": "89",
		"quote_volume": "518.86990278",
		"base_volume": "5053718.35870000",
		"quote_id": "50",
		"isFrozen": "0",
		"last_price": "0.00010475"
	},
	"ZRX_USDT": {
		"base_id": "92",
		"quote_volume": "968795.57965300",
		"base_volume": "3337211.62500000",
		"quote_id": "49",
		"isFrozen": "0",
		"last_price": "0.27700000"
	},
	"LINK_USDT": {
		"base_id": "88",
		"quote_volume": "12651715.53223653",
		"base_volume": "2778483.27320000",
		"quote_id": "49",
		"isFrozen": "0",
		"last_price": "4.33480000"
	},
	"BTC_LCNY": {
		"base_id": "50",
		"quote_volume": "3448999865.63483730",
		"base_volume": "48986.83622000",
		"quote_id": "62",
		"isFrozen": "0",
		"last_price": "67989.22000000"
	},
	"OMG_BTC": {
		"base_id": "87",
		"quote_volume": "156.15967950",
		"base_volume": "1341901.16000000",
		"quote_id": "50",
		"isFrozen": "0",
		"last_price": "0.00011538"
	},
	"PAX_LCNY": {
		"base_id": "89",
		"quote_volume": "1147637.15416479",
		"base_volume": "161757.10860000",
		"quote_id": "62",
		"isFrozen": "0",
		"last_price": "7.12030000"
	},
	"EOS_LCNY": {
		"base_id": "66",
		"quote_volume": "786681012.32149200",
		"base_volume": "26919371.94000000",
		"quote_id": "62",
		"isFrozen": "0",
		"last_price": "28.63120000"
	},
	"ETC_BTC": {
		"base_id": "54",
		"quote_volume": "759.20481161",
		"base_volume": "813756.08400000",
		"quote_id": "50",
		"isFrozen": "0",
		"last_price": "0.00093000"
	},
	"ETC_USDT": {
		"base_id": "54",
		"quote_volume": "42615661.11036400",
		"base_volume": "4596428.16100000",
		"quote_id": "49",
		"isFrozen": "0",
		"last_price": "8.88600000"
	},
	"BTC_USDT": {
		"base_id": "50",
		"quote_volume": "1248500502.03163952",
		"base_volume": "126117.99136729",
		"quote_id": "49",
		"isFrozen": "0",
		"last_price": "9556.05000000"
	},
	"XRP_BTC": {
		"base_id": "63",
		"quote_volume": "860.97967988",
		"base_volume": "29606637.53000000",
		"quote_id": "50",
		"isFrozen": "0",
		"last_price": "0.00002890"
	},
	"ZRX_BTC": {
		"base_id": "92",
		"quote_volume": "135.70404161",
		"base_volume": "4635247.79900000",
		"quote_id": "50",
		"isFrozen": "0",
		"last_price": "0.00002900"
	},
	"BCHSV_USDT": {
		"base_id": "130",
		"quote_volume": "759919.94003122",
		"base_volume": "2513.28890000",
		"quote_id": "49",
		"isFrozen": "0",
		"last_price": "299.89000000"
	},
	"BAT_LCNY": {
		"base_id": "93",
		"quote_volume": "643563.90677000",
		"base_volume": "334702.50000000",
		"quote_id": "62",
		"isFrozen": "0",
		"last_price": "1.78820000"
	},
	"XRP_USDT": {
		"base_id": "63",
		"quote_volume": "714125.02213899",
		"base_volume": "2477952.58144144",
		"quote_id": "49",
		"isFrozen": "0",
		"last_price": "0.27640000"
	},
	"ETH_LCNY": {
		"base_id": "51",
		"quote_volume": "260592523.95910840",
		"base_volume": "135049.12800000",
		"quote_id": "62",
		"isFrozen": "0",
		"last_price": "1844.58000000"
	},
	"LRC_USDT": {
		"base_id": "86",
		"quote_volume": "2111389.08346419",
		"base_volume": "52894166.41012995",
		"quote_id": "49",
		"isFrozen": "0",
		"last_price": "0.04180000"
	}
}
```

### Response Parameter Description

| Parameter | Type | Description |
| --- | --- | --- |
| JSON Key | String | market（base_quote） |
| base | string |  |
| base_id | string | The quote pair Unified Cryptoasset ID. |
| quote | string |  |
| quote_id | string |  |
| last_price | decimal | The price of the last executed order |
| base_volume | decimal | 24 hour trading volume in base pair volume |
| quote_volume | decimal | 24 hour trading volume in quote pair volume |
| isFrozen | integer | Indicates if the market is currently enabled (1) or disabled (0). |

