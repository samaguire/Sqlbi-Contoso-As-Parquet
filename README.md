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

The KQL functions come in both the original version, as per the SQLBI Contoso database, and a perpetual version, which moves forward with time. The perpetual versions and non-perpetual versions are considered to be sets and functions from differing sets should not be used together.

### Free cluster compatible

- [Contoso 10K.kql](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet/blob/main/Scripts/Azure%20Data%20Explorer/Contoso%2010K.kql)
- [Contoso 100K.kql](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet/blob/main/Scripts/Azure%20Data%20Explorer/Contoso%20100K.kql)
- [Contoso 1M.kql](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet/blob/main/Scripts/Azure%20Data%20Explorer/Contoso%201M.kql)
- [Contoso 10M.kql](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet/blob/main/Scripts/Azure%20Data%20Explorer/Contoso%2010M.kql)
- [Contoso 100M.kql](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet/blob/main/Scripts/Azure%20Data%20Explorer/Contoso%20100M.kql) (non-perpetual version)

### Paid cluster required

- [Contoso 100M.kql](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet/blob/main/Scripts/Azure%20Data%20Explorer/Contoso%20100M.kql) (perpetual version)
- [Contoso 1G.kql](https://github.com/samaguire/Sqlbi-Contoso-As-Parquet/blob/main/Scripts/Azure%20Data%20Explorer/Contoso%201G.kql)

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
