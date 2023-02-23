# Bit.Country Pioneer substrate-etl Summary (Monthly)

_Source_: [bitcountrypioneer.polkaholic.io](https://bitcountrypioneer.polkaholic.io)

*Relay Chain*: kusama
*Para ID*: 2096



| Month | Start Block | End Block | # Blocks | # Signed Extrinsics (total) | # Active Accounts (avg) | # Addresses with Balances (max) | Issues |
| ----- | ----------- | --------- | -------- | --------------------------- | ----------------------- | ------------------------------- | ------ |
| [2023-02-01 to 2023-02-23](/kusama/2096-bitcountrypioneer/2023-02-28.md) | 2,444,069 | 2,599,441 | 155,373 | 9,025 | 148 | 24,856 | -   |   
| [2023-01-01 to 2023-01-31](/kusama/2096-bitcountrypioneer/2023-01-31.md) | 2,226,701 | 2,444,068 | 217,368 | 31,043 | 332 | 24,704 | -   |   
| [2022-12-01 to 2022-12-31](/kusama/2096-bitcountrypioneer/2022-12-31.md) | 2,019,162 | 2,226,700 | 207,539 | 9,952 |  | 24,181 | -   |   
| [2022-11-01 to 2022-11-30](/kusama/2096-bitcountrypioneer/2022-11-30.md) | 1,810,421 | 2,019,161 | 208,741 | 13,243 |  | 23,665 | -   |   
| [2022-10-01 to 2022-10-31](/kusama/2096-bitcountrypioneer/2022-10-31.md) | 1,595,673 | 1,810,420 | 214,748 | 14,294 |  | 23,314 | -   |   
| [2022-09-01 to 2022-09-30](/kusama/2096-bitcountrypioneer/2022-09-30.md) | 1,402,056 | 1,595,672 | 193,617 | 14,760 |  | 22,690 | -   |   
| [2022-08-01 to 2022-08-31](/kusama/2096-bitcountrypioneer/2022-08-31.md) | 1,225,395 | 1,402,055 | 176,661 | 25,526 |  | 21,759 | -   |   
| [2022-07-01 to 2022-07-31](/kusama/2096-bitcountrypioneer/2022-07-31.md) | 1,060,505 | 1,225,394 | 164,890 | 465 |  | 16,851 | -   |   
| [2022-06-01 to 2022-06-30](/kusama/2096-bitcountrypioneer/2022-06-30.md) | 902,329 | 1,060,504 | 158,176 | 328 |  | 16,597 | -   |   
| [2022-05-01 to 2022-05-31](/kusama/2096-bitcountrypioneer/2022-05-31.md) | 750,614 | 902,328 | 151,715 | 355 |  | 16,447 | -   |   
| [2022-04-01 to 2022-04-30](/kusama/2096-bitcountrypioneer/2022-04-30.md) | 647,373 | 750,613 | 103,241 | 522 |  | 16,146 | -   |   
| [2022-03-01 to 2022-03-31](/kusama/2096-bitcountrypioneer/2022-03-31.md) | 527,686 | 647,372 | 119,687 | 1,267 |  | 15,096 | -   |   
| [2022-02-01 to 2022-02-28](/kusama/2096-bitcountrypioneer/2022-02-28.md) | 406,315 | 527,685 | 121,371 | 15 |  | 8 | -   |   
| [2022-01-01 to 2022-01-31](/kusama/2096-bitcountrypioneer/2022-01-31.md) | 213,884 | 406,314 | 192,431 | 6 |  | 6 | -   |   
| [2021-12-01 to 2021-12-31](/kusama/2096-bitcountrypioneer/2021-12-31.md) | 17,803 | 213,883 | 196,081 | 14 |  | 5 | -   |   
| [2021-11-28 to 2021-11-30](/kusama/2096-bitcountrypioneer/2021-11-30.md) | 1 | 17,802 | 17,802 |  |  | 4 | -   |   

## # Blocks
```
SELECT LAST_DAY( date(block_time)) as monthDT, Min(date(block_time)) startBN, max(date(block_time)) endBN, min(number) minBN, max(number) maxBN, count(*) numBlocks, max(number)-min(number)+1-count(*) as numBlocks_missing FROM `substrate-etl.kusama.blocks2096` group by monthDT order by monthDT desc
```



Report source: [https://cdn.polkaholic.io/substrate-etl/kusama/2096.json](https://cdn.polkaholic.io/substrate-etl/kusama/2096.json) | See [Definitions](/DEFINITIONS.md) for details
