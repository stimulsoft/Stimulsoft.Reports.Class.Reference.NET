---
title: "StiAmazonRedshiftDatabase Class"
---

## StiAmazonRedshiftDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiAmazonRedshiftDatabase
```

### Inheritance

Inherits from: StiPostgreSQLDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAmazonRedshiftDatabase**() | Creates a new object of the type StiAmazonRedshiftDatabase. |
| **StiAmazonRedshiftDatabase**(string name, string connectionString) | Creates a new object of the type StiAmazonRedshiftDatabase. |
| **StiAmazonRedshiftDatabase**(string name, string alias, string connectionString) | Creates a new object of the type StiAmazonRedshiftDatabase. |
| **StiAmazonRedshiftDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) | Creates a new object of the type StiAmazonRedshiftDatabase. |
| **StiAmazonRedshiftDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) | Creates a new object of the type StiAmazonRedshiftDatabase. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CopyDataSourceFrom** | StiDataSource |  |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/StiDataConnector.md) | Returns new data connector for this database. |
| **CreateDataSource** | [StiSqlSource](StiSqlSource.md) | Returns new data source for this database. |
| **GetConnectionStringHelper** | string |  |
| **GetDataAdapterType** | Type |  |
