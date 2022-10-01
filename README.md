# SQLBI Contoso as Parquet

This repository contains parquet files of the Contoso databases found at [https://github.com/sql-bi/Contoso-Data-Generator](https://github.com/sql-bi/Contoso-Data-Generator/releases/tag/v1.0.0).

Credit to [SQLBI](https://www.sqlbi.com/) for creating the [Contoso Data Generator](https://sql.bi/754597) tool and resources, without which this repository would not be possible.

## Parquet files

- [Contoso 10K](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet/tree/main/Contoso%2010K)
- [Contoso 100K](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet/tree/main/Contoso%20100K)
- [Contoso 1M](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet/tree/main/Contoso%201M)
- [Contoso 10M](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet/tree/main/Contoso%2010M)
- [Contoso 100M](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet/tree/main/Contoso%20100M)
- [Contoso 1G Part A](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet-1G-PartA/tree/main/Contoso%201G)
- [Contoso 1G Part B](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet-1G-PartB/tree/main/Contoso%201G)

## Azure Data Explorer

These are KQL scripts to re-create the Contoso databases in Azure Data Explorer. [Start for free using Azure Data Explorer](https://learn.microsoft.com/en-gb/azure/data-explorer/start-for-free).

NB: The KQL functions have been adapted to be perpetual, i.e. move the dates forward as time passes. If a true replication of the original databases is required, then commented code can be used in replacement of the relevant uncommented code.

### Free cluster compatible

- [Contoso 10K](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet/tree/main/Contoso%2010K)
- [Contoso 100K](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet/tree/main/Contoso%20100K)
- [Contoso 1M](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet/tree/main/Contoso%201M)
- [Contoso 10M](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet/tree/main/Contoso%2010M)
- [Contoso 100M](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet/tree/main/Contoso%20100M)

### Paid cluster required

- [Contoso 1G](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet-1G-PartA/tree/main/Contoso%201G)

### Table row counts

|  | Contoso 10K | Contoso 100K | Contoso 1M | Contoso 10M | Contoso 100M | Contoso 1G |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Data_CurrencyExchange | 202,100 | 202,100 | 202,100 | 202,100 | 202,100 | 202,100 |
| Data_Customer | 5,585 | 16,421 | 88,941 | 1,468,724 | 1,868,084 | 1,882,923 |
| Data_Date | 1,461 | 4,018 | 4,018 | 4,018 | 4,018 | 4,018 |
| Data_GeoLocations | 376 | 514 | 606 | 617 | 617 | 617 |
| Data_OrderRows | 13,915 | 208,969 | 2,237,028 | 10,144,064 | 225,616,948 | 2,259,470,276 |
| Data_Orders | 5,819 | 87,053 | 933,154 | 4,230,271 | 94,094,678 | 942,350,318 |
| Data_Product | 2,517 | 2,517 | 2,517 | 2,517 | 2,517 | 2,517 |
| Data_Store | 74 | 74 | 74 | 74 | 74 | 74 |
