---
title: "StiCosmosDbAdapterService Class"
---

## StiCosmosDbAdapterService Class

**Namespace:** `Stimulsoft.Report.Dictionary.Adapters.Azure`  
**Assembly:** `Stimulsoft.Report`

Describes the adapter for access to CosmosDbConnection.

```csharp
public class StiCosmosDbAdapterService
```

### Inheritance

Inherits from: [StiNoSqlAdapterService](../../StiNoSqlAdapterService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConnectDataSourceToData** | void |  |
| **CreateConnector** | [StiNoSqlDataConnector](../../../../Stimulsoft_Base/StiNoSqlDataConnector.md) | Returns new data connector for this type of the database. |
| **GetColumnsFromData** *(+1 overloads)* | StiDataColumnsCollection | Returns a collection of columns of data. |
| **GetDataSourceType** | Type | Returns the type of the Data Source. |
| **GetParametersFromData** | StiDataParametersCollection | Returns a collection of parameters of data. |
| **TestConnection** | string |  |
