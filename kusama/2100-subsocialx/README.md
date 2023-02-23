# SubsocialX substrate-etl Summary (Monthly)

_Source_: [subsocialx.polkaholic.io](https://subsocialx.polkaholic.io)

*Relay Chain*: kusama
*Para ID*: 2100
Status: Only partial index available: Onboarding


| Month | Start Block | End Block | # Blocks | # Signed Extrinsics (total) | # Active Accounts (avg) | # Addresses with Balances (max) | Issues |
| ----- | ----------- | --------- | -------- | --------------------------- | ----------------------- | ------------------------------- | ------ |
| [2023-02-01 to 2023-02-23](/kusama/2100-subsocialx/2023-02-28.md) | 2,115,150 | 2,270,787 | 155,638 | 1,888 | 47 | 34,322 | -   |   
| [2023-01-04 to 2023-01-31](/kusama/2100-subsocialx/2023-01-31.md) | 1,918,848 | 2,115,149 | 153,838 | 1,726 | 47 | 34,238 | - 42,464 (21.63%) |   
| [2022-12-06 to 2022-12-13](/kusama/2100-subsocialx/2022-12-31.md) | 1,723,890 | 1,774,259 | 48,469 | 475 |  |  | -  **BROKEN** (3.77%) |   
| [2022-11-01 to 2022-11-12](/kusama/2100-subsocialx/2022-11-30.md) | 1,507,933 | 1,591,419 | 82,025 | 1,568 |  |  | -  **BROKEN** (1.75%) |   
| [2022-10-01 to 2022-10-31](/kusama/2100-subsocialx/2022-10-31.md) | 1,293,052 | 1,507,932 | 214,881 | 2,227 |  | 33,976 | -   |   
| [2022-09-01 to 2022-09-30](/kusama/2100-subsocialx/2022-09-30.md) | 1,095,994 | 1,293,051 | 197,058 | 2,008 |  | 33,870 | -   |   
| [2022-08-01 to 2022-08-31](/kusama/2100-subsocialx/2022-08-31.md) | 915,848 | 1,095,993 | 180,146 | 805 |  | 33,757 | -   |   
| [2022-07-01 to 2022-07-31](/kusama/2100-subsocialx/2022-07-31.md) | 758,174 | 915,847 | 152,562 | 406 |  | 33,747 | - 5,112 (3.24%) |   
| [2022-06-01 to 2022-06-30](/kusama/2100-subsocialx/2022-06-30.md) | 569,592 | 758,173 | 188,582 | 369 |  | 33,747 | -   |   
| [2022-05-01 to 2022-05-31](/kusama/2100-subsocialx/2022-05-31.md) | 396,132 | 569,591 | 173,460 | 844 |  | 33,745 | -   |   
| [2022-04-01 to 2022-04-30](/kusama/2100-subsocialx/2022-04-30.md) | 308,836 | 396,131 | 87,292 | 6,795 |  | 33,745 | - 4 (0.00%) |   
| [2022-03-01 to 2022-03-31](/kusama/2100-subsocialx/2022-03-31.md) | 178,187 | 308,835 | 130,642 | 611 |  | 20,428 | - 7 (0.01%) |   
| [2022-02-01 to 2022-02-28](/kusama/2100-subsocialx/2022-02-28.md) | 41,996 | 178,186 | 136,191 | 479 |  | 12,036 | -   |   
| [2022-01-25 to 2022-01-31](/kusama/2100-subsocialx/2022-01-31.md) | 1 | 41,995 | 41,995 |  |  | 3 | -   |   

## # Blocks
```
SELECT LAST_DAY( date(block_time)) as monthDT, Min(date(block_time)) startBN, max(date(block_time)) endBN, min(number) minBN, max(number) maxBN, count(*) numBlocks, max(number)-min(number)+1-count(*) as numBlocks_missing FROM `substrate-etl.kusama.blocks2100` group by monthDT order by monthDT desc
```



Report source: [https://cdn.polkaholic.io/substrate-etl/kusama/2100.json](https://cdn.polkaholic.io/substrate-etl/kusama/2100.json) | See [Definitions](/DEFINITIONS.md) for details
