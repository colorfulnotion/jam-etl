# Efinity substrate-etl Summary (Monthly)

_Source_: [efinity.polkaholic.io](https://efinity.polkaholic.io)

*Relay Chain*: polkadot
*Para ID*: 2021



| Month | Start Block | End Block | # Blocks | # Signed Extrinsics (total) | # Active Accounts (avg) | # Addresses with Balances (max) | Issues |
| ----- | ----------- | --------- | -------- | --------------------------- | ----------------------- | ------------------------------- | ------ |
| [2023-02-01 to 2023-02-23](/polkadot/2021-efinity/2023-02-28.md) | 2,089,532 | 2,223,613 | 134,082 | 10,937 | 37 | 16,114 | -   |   
| [2023-01-01 to 2023-01-31](/polkadot/2021-efinity/2023-01-31.md) | 1,895,402 | 2,089,531 | 194,130 | 3,132 | 31 | 15,989 | -   |   
| [2022-12-01 to 2022-12-31](/polkadot/2021-efinity/2022-12-31.md) | 1,689,841 | 1,895,401 | 205,561 | 9,933 |  | 15,846 | -   |   
| [2022-11-01 to 2022-11-30](/polkadot/2021-efinity/2022-11-30.md) | 1,489,730 | 1,689,840 | 200,111 | 1,325 |  | 15,760 | -   |   
| [2022-10-01 to 2022-10-31](/polkadot/2021-efinity/2022-10-31.md) | 1,285,086 | 1,489,729 | 204,644 | 888 |  | 15,635 | -   |   
| [2022-09-01 to 2022-09-30](/polkadot/2021-efinity/2022-09-30.md) | 1,097,430 | 1,285,085 | 187,656 | 723 |  | 15,571 | -   |   
| [2022-08-01 to 2022-08-31](/polkadot/2021-efinity/2022-08-31.md) | 905,358 | 1,097,429 | 192,072 | 412 |  | 15,549 | -   |   
| [2022-07-01 to 2022-07-31](/polkadot/2021-efinity/2022-07-31.md) | 716,102 | 905,357 | 189,256 | 434 |  | 15,534 | -   |   
| [2022-06-01 to 2022-06-30](/polkadot/2021-efinity/2022-06-30.md) | 534,582 | 716,101 | 181,520 | 945 |  | 15,515 | -   |   
| [2022-05-01 to 2022-05-31](/polkadot/2021-efinity/2022-05-31.md) | 339,781 | 534,581 | 194,801 | 13 |  | 10 | -   |   
| [2022-04-01 to 2022-04-30](/polkadot/2021-efinity/2022-04-30.md) | 135,189 | 339,780 | 204,592 |  |  | 3 | -   |   
| [2022-03-12 to 2022-03-31](/polkadot/2021-efinity/2022-03-31.md) | 1 | 135,188 | 135,188 |  |  | 3 | -   |   

## # Blocks
```
SELECT LAST_DAY( date(block_time)) as monthDT, Min(date(block_time)) startBN, max(date(block_time)) endBN, min(number) minBN, max(number) maxBN, count(*) numBlocks, max(number)-min(number)+1-count(*) as numBlocks_missing FROM `substrate-etl.polkadot.blocks2021` group by monthDT order by monthDT desc
```



Report source: [https://cdn.polkaholic.io/substrate-etl/polkadot/2021.json](https://cdn.polkaholic.io/substrate-etl/polkadot/2021.json) | See [Definitions](/DEFINITIONS.md) for details
