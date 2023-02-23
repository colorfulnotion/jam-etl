# Kintsugi substrate-etl Summary (Monthly)

_Source_: [kintsugi.polkaholic.io](https://kintsugi.polkaholic.io)

*Relay Chain*: kusama
*Para ID*: 2092



| Month | Start Block | End Block | # Blocks | # Signed Extrinsics (total) | # Active Accounts (avg) | # Addresses with Balances (max) | Issues |
| ----- | ----------- | --------- | -------- | --------------------------- | ----------------------- | ------------------------------- | ------ |
| [2023-02-01 to 2023-02-23](/kusama/2092-kintsugi/2023-02-28.md) | 2,350,264 | 2,495,880 | 145,617 | 26,056 | 76 | 16,112 | -   |   
| [2023-01-01 to 2023-01-31](/kusama/2092-kintsugi/2023-01-31.md) | 2,142,757 | 2,350,263 | 207,507 | 36,993 | 80 | 16,042 | -   |   
| [2022-12-01 to 2022-12-31](/kusama/2092-kintsugi/2022-12-31.md) | 1,981,372 | 2,142,756 | 161,385 | 40,567 |  | 15,930 | -   |   
| [2022-11-01 to 2022-11-30](/kusama/2092-kintsugi/2022-11-30.md) | 1,786,735 | 1,981,371 | 194,637 | 40,991 |  | 15,864 | -   |   
| [2022-10-01 to 2022-10-31](/kusama/2092-kintsugi/2022-10-31.md) | 1,592,508 | 1,786,734 | 194,227 | 42,435 |  | 15,628 | -   |   
| [2022-09-01 to 2022-09-30](/kusama/2092-kintsugi/2022-09-30.md) | 1,414,110 | 1,592,507 | 178,398 | 40,588 |  | 15,468 | -   |   
| [2022-08-01 to 2022-08-31](/kusama/2092-kintsugi/2022-08-31.md) | 1,237,315 | 1,414,109 | 176,795 | 41,031 |  | 15,359 | -   |   
| [2022-07-01 to 2022-07-31](/kusama/2092-kintsugi/2022-07-31.md) | 1,085,380 | 1,237,314 | 151,935 | 34,348 |  | 8,491 | -   |   
| [2022-06-01 to 2022-06-30](/kusama/2092-kintsugi/2022-06-30.md) | 915,114 | 1,085,379 | 170,266 | 90,856 |  | 8,202 | -   |   
| [2022-05-01 to 2022-05-31](/kusama/2092-kintsugi/2022-05-31.md) | 759,813 | 915,113 | 155,301 | 130,533 |  | 8,038 | -   |   
| [2022-04-01 to 2022-04-30](/kusama/2092-kintsugi/2022-04-30.md) | 658,933 | 759,812 | 100,880 | 125,648 |  | 7,882 | -   |   
| [2022-03-01 to 2022-03-31](/kusama/2092-kintsugi/2022-03-31.md) | 537,906 | 658,932 | 121,027 | 34,161 |  | 7,402 | -   |   
| [2022-02-01 to 2022-02-28](/kusama/2092-kintsugi/2022-02-28.md) | 416,607 | 537,905 | 121,299 | 1,083 |  | 6,650 | -   |   
| [2022-01-01 to 2022-01-31](/kusama/2092-kintsugi/2022-01-31.md) | 234,870 | 416,606 | 181,737 | 3,421 |  | 6,331 | -   |   
| [2021-12-01 to 2021-12-31](/kusama/2092-kintsugi/2021-12-31.md) | 60,448 | 234,869 | 174,422 | 5,206 |  | 5,068 | -   |   
| [2021-11-01 to 2021-11-30](/kusama/2092-kintsugi/2021-11-30.md) | 27,097 | 60,447 | 33,351 | 9 | 3 | 7 | -   |   
| [2021-10-13 to 2021-10-31](/kusama/2092-kintsugi/2021-10-31.md) | 1 | 27,096 | 27,088 | 4 |  | 2 | - 8 (0.03%) |   

## # Blocks
```
SELECT LAST_DAY( date(block_time)) as monthDT, Min(date(block_time)) startBN, max(date(block_time)) endBN, min(number) minBN, max(number) maxBN, count(*) numBlocks, max(number)-min(number)+1-count(*) as numBlocks_missing FROM `substrate-etl.kusama.blocks2092` group by monthDT order by monthDT desc
```



Report source: [https://cdn.polkaholic.io/substrate-etl/kusama/2092.json](https://cdn.polkaholic.io/substrate-etl/kusama/2092.json) | See [Definitions](/DEFINITIONS.md) for details
