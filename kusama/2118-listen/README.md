# Listen substrate-etl Summary (Monthly)

_Source_: [listen.polkaholic.io](https://listen.polkaholic.io)

*Relay Chain*: kusama
*Para ID*: 2118



| Month | Start Block | End Block | # Blocks | # Signed Extrinsics (total) | # Active Accounts (avg) | # Addresses with Balances (max) | Issues |
| ----- | ----------- | --------- | -------- | --------------------------- | ----------------------- | ------------------------------- | ------ |
| [2023-02-01 to 2023-02-23](/kusama/2118-listen/2023-02-28.md) | 1,391,877 | 1,507,435 | 115,559 |  | 2 | 2,053 | -   |   
| [2023-01-01 to 2023-01-31](/kusama/2118-listen/2023-01-31.md) | 1,177,102 | 1,391,876 | 214,775 | 1 | 2 | 2,053 | -   |   
| [2022-12-01 to 2022-12-31](/kusama/2118-listen/2022-12-31.md) | 972,453 | 1,177,101 | 204,649 | 7,298 |  | 2,053 | -   |   
| [2022-11-01 to 2022-11-30](/kusama/2118-listen/2022-11-30.md) | 769,445 | 972,452 | 203,008 | 51,375 |  | 2,005 | -   |   
| [2022-10-01 to 2022-10-31](/kusama/2118-listen/2022-10-31.md) | 561,598 | 769,444 | 207,847 | 22,195 |  | 292 | -   |   
| [2022-09-01 to 2022-09-30](/kusama/2118-listen/2022-09-30.md) | 369,816 | 561,597 | 191,782 | 350 |  | 64 | -   |   
| [2022-08-01 to 2022-08-31](/kusama/2118-listen/2022-08-31.md) | 196,512 | 369,815 | 173,304 | 121 |  | 27 | -   |   
| [2022-07-01 to 2022-07-31](/kusama/2118-listen/2022-07-31.md) | 22,044 | 196,511 | 174,468 | 40 |  | 15 | -   |   
| [2022-06-27 to 2022-06-30](/kusama/2118-listen/2022-06-30.md) | 1 | 22,043 | 22,043 | 18 |  | 9 | -   |   

## # Blocks
```
SELECT LAST_DAY( date(block_time)) as monthDT, Min(date(block_time)) startBN, max(date(block_time)) endBN, min(number) minBN, max(number) maxBN, count(*) numBlocks, max(number)-min(number)+1-count(*) as numBlocks_missing FROM `substrate-etl.kusama.blocks2118` group by monthDT order by monthDT desc
```



Report source: [https://cdn.polkaholic.io/substrate-etl/kusama/2118.json](https://cdn.polkaholic.io/substrate-etl/kusama/2118.json) | See [Definitions](/DEFINITIONS.md) for details
