# Bifrost-Kusama substrate-etl Summary (Monthly)

_Source_: [bifrost-ksm.polkaholic.io](https://bifrost-ksm.polkaholic.io)

*Relay Chain*: kusama
*Para ID*: 2001



| Month | Start Block | End Block | # Blocks | # Signed Extrinsics (total) | # Active Accounts (avg) | # Addresses with Balances (max) | Issues |
| ----- | ----------- | --------- | -------- | --------------------------- | ----------------------- | ------------------------------- | ------ |
| [2023-02-01 to 2023-02-23](/kusama/2001-bifrost-ksm/2023-02-28.md) | 3,444,040 | 3,599,586 | 154,964 | 36,366 | 206 | 101,433 | - 583 (0.37%) |   
| [2023-01-01 to 2023-01-31](/kusama/2001-bifrost-ksm/2023-01-31.md) | 3,225,421 | 3,444,039 | 218,619 | 43,582 | 199 | 101,184 | -   |   
| [2022-12-01 to 2022-12-31](/kusama/2001-bifrost-ksm/2022-12-31.md) | 3,014,958 | 3,225,420 | 210,463 | 30,796 |  | 100,939 | -   |   
| [2022-11-01 to 2022-11-30](/kusama/2001-bifrost-ksm/2022-11-30.md) | 2,804,503 | 3,014,957 | 210,455 | 23,381 |  | 100,775 | -   |   
| [2022-10-01 to 2022-10-31](/kusama/2001-bifrost-ksm/2022-10-31.md) | 2,587,488 | 2,804,502 | 217,015 | 13,533 |  | 100,561 | -   |   
| [2022-09-01 to 2022-09-30](/kusama/2001-bifrost-ksm/2022-09-30.md) | 2,387,266 | 2,587,487 | 200,222 | 13,162 |  | 100,405 | -   |   
| [2022-08-01 to 2022-08-31](/kusama/2001-bifrost-ksm/2022-08-31.md) | 2,204,050 | 2,387,265 | 183,216 | 27,346 |  | 100,175 | -   |   
| [2022-07-01 to 2022-07-31](/kusama/2001-bifrost-ksm/2022-07-31.md) | 2,023,126 | 2,204,049 | 180,924 | 22,130 |  | 99,607 | -   |   
| [2022-06-01 to 2022-06-30](/kusama/2001-bifrost-ksm/2022-06-30.md) | 1,834,935 | 2,023,125 | 188,191 | 22,351 |  | 99,396 | -   |   
| [2022-05-01 to 2022-05-31](/kusama/2001-bifrost-ksm/2022-05-31.md) | 1,660,921 | 1,834,934 | 174,014 | 25,973 |  | 99,134 | -   |   
| [2022-04-01 to 2022-04-30](/kusama/2001-bifrost-ksm/2022-04-30.md) | 1,544,029 | 1,660,920 | 116,892 | 23,780 |  | 98,761 | -   |   
| [2022-03-01 to 2022-03-31](/kusama/2001-bifrost-ksm/2022-03-31.md) | 1,413,189 | 1,544,028 | 130,840 | 22,488 |  | 98,241 | -   |   
| [2022-02-01 to 2022-02-28](/kusama/2001-bifrost-ksm/2022-02-28.md) | 1,280,330 | 1,413,188 | 132,859 | 12,760 |  | 95,289 | -   |   
| [2022-01-01 to 2022-01-31](/kusama/2001-bifrost-ksm/2022-01-31.md) | 1,066,657 | 1,280,329 | 213,673 | 40,270 |  | 95,109 | -   |   
| [2021-12-01 to 2021-12-31](/kusama/2001-bifrost-ksm/2021-12-31.md) | 854,160 | 1,066,656 | 212,497 | 65,997 |  | 94,834 | -   |   
| [2021-11-01 to 2021-11-30](/kusama/2001-bifrost-ksm/2021-11-30.md) | 673,631 | 854,159 | 180,529 | 147,150 |  | 93,407 | -   |   
| [2021-10-01 to 2021-10-31](/kusama/2001-bifrost-ksm/2021-10-31.md) | 480,188 | 673,630 | 193,443 | 35,019 |  | 57,560 | -   |   
| [2021-09-01 to 2021-09-30](/kusama/2001-bifrost-ksm/2021-09-30.md) | 274,582 | 480,187 | 205,606 | 11,125 | 11 | 55,959 | -   |   
| [2021-08-01 to 2021-08-31](/kusama/2001-bifrost-ksm/2021-08-31.md) | 74,124 | 274,581 | 200,458 | 1,139 |  | 55,215 | -   |   
| [2021-07-20 to 2021-07-31](/kusama/2001-bifrost-ksm/2021-07-31.md) | 1 | 74,123 | 74,123 | 27 |  | 51,949 | -   |   

## # Blocks
```
SELECT LAST_DAY( date(block_time)) as monthDT, Min(date(block_time)) startBN, max(date(block_time)) endBN, min(number) minBN, max(number) maxBN, count(*) numBlocks, max(number)-min(number)+1-count(*) as numBlocks_missing FROM `substrate-etl.kusama.blocks2001` group by monthDT order by monthDT desc
```



Report source: [https://cdn.polkaholic.io/substrate-etl/kusama/2001.json](https://cdn.polkaholic.io/substrate-etl/kusama/2001.json) | See [Definitions](/DEFINITIONS.md) for details
