# Snow substrate-etl Summary (Monthly)

_Source_: [snow.polkaholic.io](https://snow.polkaholic.io)

*Relay Chain*: kusama
*Para ID*: 2129
Status: Only partial index available: Archive node unavailable


| Month | Start Block | End Block | # Blocks | # Signed Extrinsics (total) | # Active Accounts (avg) | # Addresses with Balances (max) | Issues |
| ----- | ----------- | --------- | -------- | --------------------------- | ----------------------- | ------------------------------- | ------ |
| [2023-02-08 to 2023-02-23](/kusama/2129-snow/2023-02-28.md) | 937,108 | 1,036,933 | 99,826 | 292 |  |  | -   |   
| [2023-01-01 to 2023-01-30](/kusama/2129-snow/2023-01-31.md) | 666,173 | 872,871 | 191,618 | 339 | 4 | 5,580 | -  **BROKEN** (7.30%) |   
| [2022-12-01 to 2022-12-13](/kusama/2129-snow/2022-12-31.md) | 456,754 | 539,967 | 83,214 | 274 | 7 | 5,293 | -  **BROKEN**  |   
| [2022-11-01 to 2022-11-30](/kusama/2129-snow/2022-11-30.md) | 254,577 | 456,753 | 125,549 | 2,039 |  |  | - 76,628 (37.90%) |   
| [2022-10-26 to 2022-10-31](/kusama/2129-snow/2022-10-31.md) | 218,593 | 254,576 | 35,767 | 5,804 |  |  | - 217 (0.60%) |   

## # Blocks
```
SELECT LAST_DAY( date(block_time)) as monthDT, Min(date(block_time)) startBN, max(date(block_time)) endBN, min(number) minBN, max(number) maxBN, count(*) numBlocks, max(number)-min(number)+1-count(*) as numBlocks_missing FROM `substrate-etl.kusama.blocks2129` group by monthDT order by monthDT desc
```



Report source: [https://cdn.polkaholic.io/substrate-etl/kusama/2129.json](https://cdn.polkaholic.io/substrate-etl/kusama/2129.json) | See [Definitions](/DEFINITIONS.md) for details
