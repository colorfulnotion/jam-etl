# Parallel Heiko substrate-etl Summary (Monthly)

_Source_: [parallel-heiko.polkaholic.io](https://parallel-heiko.polkaholic.io)

*Relay Chain*: kusama
*Para ID*: 2085



| Month | Start Block | End Block | # Blocks | # Signed Extrinsics (total) | # Active Accounts (avg) | # Addresses with Balances (max) | Issues |
| ----- | ----------- | --------- | -------- | --------------------------- | ----------------------- | ------------------------------- | ------ |
| [2023-02-01 to 2023-02-23](/kusama/2085-parallel-heiko/2023-02-28.md) | 2,886,511 | 3,041,416 | 153,537 | 100,275 | 94 | 24,296 | - 1,369 (0.88%) |   
| [2023-01-01 to 2023-01-31](/kusama/2085-parallel-heiko/2023-01-31.md) | 2,670,416 | 2,886,510 | 216,095 | 133,798 | 125 | 24,230 | -   |   
| [2022-12-01 to 2022-12-31](/kusama/2085-parallel-heiko/2022-12-31.md) | 2,460,859 | 2,670,415 | 209,557 | 122,059 |  | 24,126 | -   |   
| [2022-11-01 to 2022-11-30](/kusama/2085-parallel-heiko/2022-11-30.md) | 2,250,574 | 2,460,858 | 210,285 | 145,455 |  | 23,740 | -   |   
| [2022-10-01 to 2022-10-31](/kusama/2085-parallel-heiko/2022-10-31.md) | 2,034,493 | 2,250,573 | 216,081 | 120,627 |  | 25,665 | -   |   
| [2022-09-01 to 2022-09-30](/kusama/2085-parallel-heiko/2022-09-30.md) | 1,835,234 | 2,034,492 | 199,259 | 105,649 |  | 22,490 | -   |   
| [2022-08-01 to 2022-08-31](/kusama/2085-parallel-heiko/2022-08-31.md) | 1,652,800 | 1,835,233 | 182,434 | 70,134 |  | 20,859 | -   |   
| [2022-07-01 to 2022-07-31](/kusama/2085-parallel-heiko/2022-07-31.md) | 1,471,509 | 1,652,799 | 181,291 | 67,754 |  | 13,988 | -   |   
| [2022-06-01 to 2022-06-30](/kusama/2085-parallel-heiko/2022-06-30.md) | 1,281,017 | 1,471,508 | 190,492 | 70,417 |  | 12,625 | -   |   
| [2022-05-01 to 2022-05-31](/kusama/2085-parallel-heiko/2022-05-31.md) | 1,104,732 | 1,281,016 | 176,285 | 77,810 |  | 12,323 | -   |   
| [2022-04-01 to 2022-04-30](/kusama/2085-parallel-heiko/2022-04-30.md) | 988,255 | 1,104,731 | 116,477 | 110,573 |  | 11,851 | -   |   
| [2022-03-01 to 2022-03-31](/kusama/2085-parallel-heiko/2022-03-31.md) | 854,195 | 988,254 | 134,060 | 205,972 |  | 11,287 | -   |   
| [2022-02-01 to 2022-02-28](/kusama/2085-parallel-heiko/2022-02-28.md) | 719,649 | 854,194 | 134,546 | 217,052 |  | 10,959 | -   |   
| [2022-01-01 to 2022-01-31](/kusama/2085-parallel-heiko/2022-01-31.md) | 507,938 | 719,648 | 211,711 | 310,790 |  | 10,917 | -   |   
| [2021-12-01 to 2021-12-31](/kusama/2085-parallel-heiko/2021-12-31.md) | 301,531 | 507,937 | 206,407 | 320,717 |  | 10,773 | -   |   
| [2021-11-01 to 2021-11-30](/kusama/2085-parallel-heiko/2021-11-30.md) | 144,846 | 301,530 | 156,685 | 258,147 |  | 10,718 | -   |   
| [2021-10-06 to 2021-10-31](/kusama/2085-parallel-heiko/2021-10-31.md) | 1 | 144,845 | 144,845 | 36,267 |  | 16 | -   |   

## # Blocks
```
SELECT LAST_DAY( date(block_time)) as monthDT, Min(date(block_time)) startBN, max(date(block_time)) endBN, min(number) minBN, max(number) maxBN, count(*) numBlocks, max(number)-min(number)+1-count(*) as numBlocks_missing FROM `substrate-etl.kusama.blocks2085` group by monthDT order by monthDT desc
```



Report source: [https://cdn.polkaholic.io/substrate-etl/kusama/2085.json](https://cdn.polkaholic.io/substrate-etl/kusama/2085.json) | See [Definitions](/DEFINITIONS.md) for details
