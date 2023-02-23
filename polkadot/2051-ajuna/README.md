# Ajuna substrate-etl Summary (Monthly)

_Source_: [ajuna.polkaholic.io](https://ajuna.polkaholic.io)

*Relay Chain*: polkadot
*Para ID*: 2051



| Month | Start Block | End Block | # Blocks | # Signed Extrinsics (total) | # Active Accounts (avg) | # Addresses with Balances (max) | Issues |
| ----- | ----------- | --------- | -------- | --------------------------- | ----------------------- | ------------------------------- | ------ |
| [2023-02-01 to 2023-02-23](/polkadot/2051-ajuna/2023-02-28.md) | 486,290 | 636,896 | 150,607 |  | 4 | 7 | -   |   
| [2023-01-01 to 2023-01-31](/polkadot/2051-ajuna/2023-01-31.md) | 277,227 | 486,289 | 209,063 | 3 | 4 | 7 | -   |   
| [2022-12-01 to 2022-12-31](/polkadot/2051-ajuna/2022-12-31.md) | 65,407 | 277,226 | 211,820 |  |  | 6 | -   |   
| [2022-11-21 to 2022-11-30](/polkadot/2051-ajuna/2022-11-30.md) | 1 | 65,406 | 65,406 | 9 |  | 6 | -   |   

## # Blocks
```
SELECT LAST_DAY( date(block_time)) as monthDT, Min(date(block_time)) startBN, max(date(block_time)) endBN, min(number) minBN, max(number) maxBN, count(*) numBlocks, max(number)-min(number)+1-count(*) as numBlocks_missing FROM `substrate-etl.polkadot.blocks2051` group by monthDT order by monthDT desc
```



Report source: [https://cdn.polkaholic.io/substrate-etl/polkadot/2051.json](https://cdn.polkaholic.io/substrate-etl/polkadot/2051.json) | See [Definitions](/DEFINITIONS.md) for details
