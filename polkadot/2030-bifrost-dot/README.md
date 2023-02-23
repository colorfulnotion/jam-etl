# Bifrost-Polkadot substrate-etl Summary (Monthly)

_Source_: [bifrost-dot.polkaholic.io](https://bifrost-dot.polkaholic.io)

*Relay Chain*: polkadot
*Para ID*: 2030



| Month | Start Block | End Block | # Blocks | # Signed Extrinsics (total) | # Active Accounts (avg) | # Addresses with Balances (max) | Issues |
| ----- | ----------- | --------- | -------- | --------------------------- | ----------------------- | ------------------------------- | ------ |
| [2023-02-01 to 2023-02-23](/polkadot/2030-bifrost-dot/2023-02-28.md) | 1,645,275 | 1,801,132 | 155,858 | 9,664 | 100 | 3,791 | -   |   
| [2023-01-01 to 2023-01-31](/polkadot/2030-bifrost-dot/2023-01-31.md) | 1,426,953 | 1,645,274 | 218,322 | 9,277 | 77 | 3,575 | -   |   
| [2022-12-01 to 2022-12-31](/polkadot/2030-bifrost-dot/2022-12-31.md) | 1,212,434 | 1,426,952 | 214,519 | 9,329 |  | 3,412 | -   |   
| [2022-11-01 to 2022-11-30](/polkadot/2030-bifrost-dot/2022-11-30.md) | 1,013,658 | 1,212,433 | 198,776 | 6,790 |  | 3,188 | -   |   
| [2022-10-01 to 2022-10-31](/polkadot/2030-bifrost-dot/2022-10-31.md) | 799,904 | 1,013,657 | 213,754 | 3,002 |  | 2,943 | -   |   
| [2022-09-01 to 2022-09-30](/polkadot/2030-bifrost-dot/2022-09-30.md) | 593,248 | 799,903 | 206,656 | 3,397 |  | 2,805 | -   |   
| [2022-08-01 to 2022-08-31](/polkadot/2030-bifrost-dot/2022-08-31.md) | 380,234 | 593,247 | 213,014 | 161 |  | 1,333 | -   |   
| [2022-07-01 to 2022-07-31](/polkadot/2030-bifrost-dot/2022-07-31.md) | 175,695 | 380,233 | 204,539 | 10 |  | 6 | -   |   
| [2022-06-04 to 2022-06-30](/polkadot/2030-bifrost-dot/2022-06-30.md) | 1 | 175,694 | 175,694 |  |  | 6 | -   |   

## # Blocks
```
SELECT LAST_DAY( date(block_time)) as monthDT, Min(date(block_time)) startBN, max(date(block_time)) endBN, min(number) minBN, max(number) maxBN, count(*) numBlocks, max(number)-min(number)+1-count(*) as numBlocks_missing FROM `substrate-etl.polkadot.blocks2030` group by monthDT order by monthDT desc
```



Report source: [https://cdn.polkaholic.io/substrate-etl/polkadot/2030.json](https://cdn.polkaholic.io/substrate-etl/polkadot/2030.json) | See [Definitions](/DEFINITIONS.md) for details
