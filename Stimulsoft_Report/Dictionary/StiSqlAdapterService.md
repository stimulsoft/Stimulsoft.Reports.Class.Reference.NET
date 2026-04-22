---
title: "StiSqlAdapterService Class"
---

## StiSqlAdapterService Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

Describes the adapter for access to SqlConnection.

```csharp
public class StiSqlAdapterService
```

### Inheritance

Inherits from: [StiDataStoreAdapterService](StiDataStoreAdapterService.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **UseFailedConnectionsCache** `static` | bool | Gets or sets a value indicating whether to use failed connections cache to prevent performance degradation. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CloseConnection** | void |  |
| **ConnectDataSourceToData** | void |  |
| **CreateConnectionInDataStore** | void |  |
| **CreateConnector** *(+1 overloads)* | [StiSqlDataConnector](../../Stimulsoft_Base/StiSqlDataConnector.md) | Returns new data connector for this type of the database. |
| **GetColumnsFromData** *(+1 overloads)* | StiDataColumnsCollection | Returns a collection of columns of data. |
| **GetDataCategoryName** | string | Returns name of category for data. |
| **GetDataSourceType** | Type | Returns the type of the Data Source. |
| **GetDataTypes** | Type[] | Returns the array of data types to which the Data Source may refer. |
| **GetParametersFromData** | StiDataParametersCollection | Returns a collection of parameters of data. |
| **IsAdapterDataType** | bool | Returns true if the specified type is supported by this data adapters. |
| **OpenConnection** *(+1 overloads)* | void |  |
| **SetDataSourceNames** | void | Fills a name and alias of the Data Source relying on data. |
| **TestConnection** | string |  |
