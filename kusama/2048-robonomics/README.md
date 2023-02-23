# Robonomics substrate-etl Summary (Monthly)

_Source_: [robonomics.polkaholic.io](https://robonomics.polkaholic.io)

*Relay Chain*: kusama
*Para ID*: 2048



| Month | Start Block | End Block | # Blocks | # Signed Extrinsics (total) | # Active Accounts (avg) | # Addresses with Balances (max) | Issues |
| ----- | ----------- | --------- | -------- | --------------------------- | ----------------------- | ------------------------------- | ------ |
| [2023-02-01 to 2023-02-23](/kusama/2048-robonomics/2023-02-28.md) | 2,385,571 | 2,543,033 | 157,463 | 29,919 | 34 | 3,138 | -   |   
| [2023-01-01 to 2023-01-31](/kusama/2048-robonomics/2023-01-31.md) | 2,165,671 | 2,385,570 | 219,900 | 36,137 | 32 | 3,077 | -   |   
| [2022-12-01 to 2022-12-31](/kusama/2048-robonomics/2022-12-31.md) | 1,953,566 | 2,165,670 | 212,105 | 46,241 |  | 3,001 | -   |   
| [2022-11-01 to 2022-11-30](/kusama/2048-robonomics/2022-11-30.md) | 1,741,172 | 1,953,565 | 212,394 | 44,396 |  | 2,907 | -   |   
| [2022-10-01 to 2022-10-31](/kusama/2048-robonomics/2022-10-31.md) | 1,521,856 | 1,741,171 | 219,316 | 36,235 |  | 2,865 | -   |   
| [2022-09-01 to 2022-09-30](/kusama/2048-robonomics/2022-09-30.md) | 1,318,927 | 1,521,855 | 202,929 | 47,205 |  | 2,783 | -   |   
| [2022-08-01 to 2022-08-31](/kusama/2048-robonomics/2022-08-31.md) | 1,132,818 | 1,318,926 | 186,109 | 219,335 |  | 2,707 | -   |   
| [2022-07-01 to 2022-07-31](/kusama/2048-robonomics/2022-07-31.md) | 947,513 | 1,132,817 | 185,305 | 685,086 |  | 2,664 | -   |   
| [2022-06-01 to 2022-06-30](/kusama/2048-robonomics/2022-06-30.md) | 751,435 | 947,512 | 196,078 | 686,111 |  | 2,615 | -   |   
| [2022-05-01 to 2022-05-31](/kusama/2048-robonomics/2022-05-31.md) | 569,336 | 751,434 | 182,099 | 795,478 |  | 2,564 | -   |   
| [2022-04-01 to 2022-04-30](/kusama/2048-robonomics/2022-04-30.md) | 442,337 | 569,335 | 126,999 | 467,661 |  | 2,544 | -   |   
| [2022-03-01 to 2022-03-31](/kusama/2048-robonomics/2022-03-31.md) | 298,595 | 442,336 | 143,742 | 456,332 |  | 2,529 | -   |   
| [2022-02-01 to 2022-02-28](/kusama/2048-robonomics/2022-02-28.md) | 158,459 | 298,594 | 140,136 | 599,259 |  | 2,452 | -   |   
| [2022-01-09 to 2022-01-31](/kusama/2048-robonomics/2022-01-31.md) | 1 | 158,458 | 158,458 | 219,693 |  | 2,357 | -   |   

## # Blocks
```
SELECT LAST_DAY( date(block_time)) as monthDT, Min(date(block_time)) startBN, max(date(block_time)) endBN, min(number) minBN, max(number) maxBN, count(*) numBlocks, max(number)-min(number)+1-count(*) as numBlocks_missing FROM `substrate-etl.kusama.blocks2048` group by monthDT order by monthDT desc
```



Report source: [https://cdn.polkaholic.io/substrate-etl/kusama/2048.json](https://cdn.polkaholic.io/substrate-etl/kusama/2048.json) | See [Definitions](/DEFINITIONS.md) for details
