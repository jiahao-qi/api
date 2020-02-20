## assets

### Summary：

```The assets endpoint is to provide a detailed summary for each currency available on the exchange.```

### Request URL:

```https://open.loex.io/open/v1/assets```

### Request:

```GET```

### Command
```curl -X GET https://open.loex.io/open/v1/assets```

### Request frequency:

```5times / 1s```

### Response Sample:

```
{
	"code": "0",
	"message": null,
	"data": {
		"BTC": {
			"max_withdraw": "2.00000000",
			"maker_fee": "0.00200000",
			"name": "Bitcoin",
			"taker_fee": "0.00200000",
			"can_withdraw": "true",
			"can_deposit": "true",
			"unified_cryptoasset_id": "50",
			"min_withdraw": "0.00100000"
		},
		"ETH": {
			"max_withdraw": "60.00000000",
			"maker_fee": "0.00200000",
			"name": "Ethereum",
			"taker_fee": "0.00200000",
			"can_withdraw": "true",
			"can_deposit": "true",
			"unified_cryptoasset_id": "51",
			"min_withdraw": "0.02000000"
		}
	}
}
```
### Response Parameter Description

| Parameter | Type | Description |
| --- | --- | --- |
| name | string | Name of cryptocurrency. |
| unified_cryptoasset_id | integer | Unique ID of cryptocurrency assigned by Unified Cryptoasset ID. |
| can_withdraw | boolean | Identifies whether withdraws are enabled or disabled. |
| can_deposit | boolean | Identifies whether deposits are enabled or disabled. |
| min_withdraw | decimal | Identifies the single minimum withdraw amount of a cryptocurrency. |
| max_withdraw | decimal | Identifies the single maximum withdraw amount of a cryptocurrency. |
| maker_fee | decimal | Fees applied when liquidity is added to the order book. |
| taker_fee | decimal | Fees applied when liquidity is removed from the order book. |
