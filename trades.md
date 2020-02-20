## trades
### Summary：

```The trades endpoint is to return data on all recently completed trades for a given market pair.```

### Request URL：

```https://open.loex.io/open/v1/trades/market_pair```

### Request：

```GET```

### Command :

```https://open.loex.io/open/v1/trades/market_pair?market_pair=BTC_USDT```

### Request frequency：

```5 times/1s```

### Response Parameter Description

| Parameter | Type | Description |
| --- | --- | --- |
| market_pair | string | A pair such as BTC_USDT. | Mandatory |
| type/side | string | Query buy side or sell side only. | Recommended |

### Response Sample

```
{
	"code": "0",
	"message": null,
	"data": [{
		"trade_timestamp": "1582186003",
		"price": "9602.8",
		"quote_volume": "2183.484664",
		"base_volume": "0.22738",
		"type": "buy",
		"tradeID": 17631607
	}, {
		"trade_timestamp": "1582186003",
		"price": "9601.65",
		"quote_volume": "45022.328883",
		"base_volume": "4.68902",
		"type": "buy",
		"tradeID": 17631606
	}, {
		"trade_timestamp": "1582186002",
		"price": "9599.75",
		"quote_volume": "9783.0092275",
		"base_volume": "1.01909",
		"type": "buy",
		"tradeID": 17631605
	}, {
		"trade_timestamp": "1582186001",
		"price": "9599.75",
		"quote_volume": "14083.793225",
		"base_volume": "1.4671",
		"type": "buy",
		"tradeID": 17631604
	}, {
		"trade_timestamp": "1582186000",
		"price": "9599.75",
		"quote_volume": "7160.1655325",
		"base_volume": "0.74587",
		"type": "buy",
		"tradeID": 17631603
	}, {
		"trade_timestamp": "1582185998",
		"price": "9599.75",
		"quote_volume": "3143.534135",
		"base_volume": "0.32746",
		"type": "buy",
		"tradeID": 17631602
	}, {
		"trade_timestamp": "1582185998",
		"price": "9599.75",
		"quote_volume": "5145.7539925",
		"base_volume": "0.53603",
		"type": "buy",
		"tradeID": 17631601
	}, {
		"trade_timestamp": "1582185997",
		"price": "9599.75",
		"quote_volume": "41112.5613325",
		"base_volume": "4.28267",
		"type": "buy",
		"tradeID": 17631600
	}, {
		"trade_timestamp": "1582185997",
		"price": "9599.75",
		"quote_volume": "3900.8584125",
		"base_volume": "0.40635",
		"type": "buy",
		"tradeID": 17631599
	}, {
		"trade_timestamp": "1582185995",
		"price": "9599.75",
		"quote_volume": "10417.6487",
		"base_volume": "1.0852",
		"type": "buy",
		"tradeID": 17631598
	}, {
		"trade_timestamp": "1582185994",
		"price": "9599.75",
		"quote_volume": "25021.364385",
		"base_volume": "2.60646",
		"type": "buy",
		"tradeID": 17631597
	}, {
		"trade_timestamp": "1582185994",
		"price": "9599.7",
		"quote_volume": "311.510265",
		"base_volume": "0.03245",
		"type": "buy",
		"tradeID": 17631596
	}, {
		"trade_timestamp": "1582185994",
		"price": "9599.4",
		"quote_volume": "1552.894938",
		"base_volume": "0.16177",
		"type": "buy",
		"tradeID": 17631595
	}, {
		"trade_timestamp": "1582185994",
		"price": "9599.3",
		"quote_volume": "1494.61101",
		"base_volume": "0.1557",
		"type": "buy",
		"tradeID": 17631594
	}, {
		"trade_timestamp": "1582185994",
		"price": "9599.1",
		"quote_volume": "239.9775",
		"base_volume": "0.025",
		"type": "buy",
		"tradeID": 17631593
	}, {
		"trade_timestamp": "1582185994",
		"price": "9598.8",
		"quote_volume": "10028.3463",
		"base_volume": "1.04475",
		"type": "buy",
		"tradeID": 17631592
	}, {
		"trade_timestamp": "1582185994",
		"price": "9598.7",
		"quote_volume": "8219.846745",
		"base_volume": "0.85635",
		"type": "buy",
		"tradeID": 17631591
	}, {
		"trade_timestamp": "1582185994",
		"price": "9598.65",
		"quote_volume": "79.9567545",
		"base_volume": "0.00833",
		"type": "buy",
		"tradeID": 17631590
	}, {
		"trade_timestamp": "1582185993",
		"price": "9598.65",
		"quote_volume": "7954.6892145",
		"base_volume": "0.82873",
		"type": "buy",
		"tradeID": 17631589
	}, {
		"trade_timestamp": "1582185993",
		"price": "9598.6",
		"quote_volume": "1494.50202",
		"base_volume": "0.1557",
		"type": "buy",
		"tradeID": 17631588
	}, {
		"trade_timestamp": "1582185993",
		"price": "9598.4",
		"quote_volume": "149.447088",
		"base_volume": "0.01557",
		"type": "buy",
		"tradeID": 17631587
	}, {
		"trade_timestamp": "1582185993",
		"price": "9598.3",
		"quote_volume": "273.167618",
		"base_volume": "0.02846",
		"type": "buy",
		"tradeID": 17631586
	}, {
		"trade_timestamp": "1582185993",
		"price": "9598.2",
		"quote_volume": "7560.98205",
		"base_volume": "0.78775",
		"type": "buy",
		"tradeID": 17631585
	}, {
		"trade_timestamp": "1582185993",
		"price": "9598.1",
		"quote_volume": "3510.793018",
		"base_volume": "0.36578",
		"type": "buy",
		"tradeID": 17631584
	}, {
		"trade_timestamp": "1582185993",
		"price": "9597.6",
		"quote_volume": "311.538096",
		"base_volume": "0.03246",
		"type": "buy",
		"tradeID": 17631583
	}, {
		"trade_timestamp": "1582185993",
		"price": "9597.4",
		"quote_volume": "623.063208",
		"base_volume": "0.06492",
		"type": "buy",
		"tradeID": 17631582
	}, {
		"trade_timestamp": "1582185992",
		"price": "9597.3",
		"quote_volume": "6201.391368",
		"base_volume": "0.64616",
		"type": "buy",
		"tradeID": 17631581
	}, {
		"trade_timestamp": "1582185992",
		"price": "9596.7",
		"quote_volume": "311.316948",
		"base_volume": "0.03244",
		"type": "buy",
		"tradeID": 17631580
	}, {
		"trade_timestamp": "1582185992",
		"price": "9595.65",
		"quote_volume": "13744.5211905",
		"base_volume": "1.43237",
		"type": "buy",
		"tradeID": 17631579
	}, {
		"trade_timestamp": "1582185992",
		"price": "9595.65",
		"quote_volume": "4110.392634",
		"base_volume": "0.42836",
		"type": "buy",
		"tradeID": 17631578
	}]
}
```

### Response Parameter Description

| Parameter | Type | Description |
| --- | --- | --- |
| trade_id | integer | A unique ID associated with the trade for the currency pair transactionNote: Unix timestamp does not qualify as trade_id. |
| price | decimal | Transaction price in base pair volume. |
| base_volume | decimal | Transaction amount in base pair volume. |
| quote_volume | decimal | Transaction amount in quote pair volume. |
| trade_timestamp | timestamp | Unix timestamp in milliseconds for when the transaction occurred. |
| type | string | Used to determine whether or not the transaction originated as a buy or sell. |

