# Crust substrate-etl Summary (Monthly)

_Source_: [crust.polkaholic.io](https://crust.polkaholic.io)

*Relay Chain*: polkadot
*Para ID*: 2008



| Month | Start Block | End Block | # Blocks | # Signed Extrinsics (total) | # Active Accounts (avg) | # Addresses with Balances (max) | Issues |
| ----- | ----------- | --------- | -------- | --------------------------- | ----------------------- | ------------------------------- | ------ |
| [2023-02-01 to 2023-02-23](/polkadot/2008-crust/2023-02-28.md) | 504,230 | 660,429 | 156,200 | 22 | 4 | 991 | -   |   
| [2023-01-01 to 2023-01-31](/polkadot/2008-crust/2023-01-31.md) | 285,366 | 504,229 | 218,736 |  | 4 | 974 | - 128 (0.06%) |   
| [2022-12-01 to 2022-12-31](/polkadot/2008-crust/2022-12-31.md) | 67,183 | 285,365 | 218,183 |  |  | 9 | -   |   
| [2022-11-21 to 2022-11-30](/polkadot/2008-crust/2022-11-30.md) | 1 | 67,182 | 67,182 |  |  | 9 | -   |   
| [2022-10-26 to 2022-10-26](/polkadot/2008-crust/2022-10-31.md) | 288,820 | 289,071 | 252 |  |  |  | -   |   

## # Blocks
```
SELECT LAST_DAY( date(block_time)) as monthDT, Min(date(block_time)) startBN, max(date(block_time)) endBN, min(number) minBN, max(number) maxBN, count(*) numBlocks, max(number)-min(number)+1-count(*) as numBlocks_missing FROM `substrate-etl.polkadot.blocks2008` group by monthDT order by monthDT desc
```



Report source: [https://cdn.polkaholic.io/substrate-etl/polkadot/2008.json](https://cdn.polkaholic.io/substrate-etl/polkadot/2008.json) | See [Definitions](/DEFINITIONS.md) for details
