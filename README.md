# Weather lakehouse: dataproduct

An intuitive data product for weather prediction using ETL/ELT, S3, Postgres' Gold, NestJS with Cognito, lambda, and PowerBI. 

> **STATE:** In development (P1).
> **Next goal:** ETL Bronze/Silver/Gold and basic reading API


---

> **Architecture**: In order to build this product using AWS, a Medallion pattern will be used for data. At the same time, an Hexagonal pattern will be used inside a Modular Monolith, making sure all technologies here can dialog between them without an issue.
