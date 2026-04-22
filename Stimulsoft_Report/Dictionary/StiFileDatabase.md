---
title: "StiFileDatabase Class"
---

## StiFileDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public abstract class StiFileDatabase
```

### Inheritance

Inherits from: StiDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiFileDatabase()` |  |
| `StiFileDatabase(string name, string pathData)` |  |
| `StiFileDatabase(string name, string pathData, string key)` |  |
| `StiFileDatabase(string name, string pathData, string key, [StiColumnTypeProcessing](StiColumnTypeProcessing.md) castToColumnType)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **PathData** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyDatabaseInformation** *(+1 overloads)* | void | Adds tables, views and stored procedures to report dictionary from database information. |
| **CopyDataSourceFrom** | StiDataSource |  |
| **CreateDataSources** | void |  |
| **CreateDataSourcesAsync** | Task |  |
| **CreateFileConnector** | [StiFileDataConnector](../../Stimulsoft_Base/StiFileDataConnector.md) | Returns new file connector for this database. |
| **FetchSiblingDataSources** | IEnumerable<[IStiAppDataSource](../../Stimulsoft_Base/IStiAppDataSource.md)> |  |
| **GetConnectorOptions** | [StiFileDataOptions](../../Stimulsoft_Base/StiFileDataOptions.md) |  |
| **GetDatabaseInformation** | [StiDatabaseInformation](StiDatabaseInformation.md) | Returns full database information. |
| **LoadFromJsonObject** | void |  |
| **ParsePath** | string |  |
| **RegData** *(+1 overloads)* | void | Registers the database in dictionary. |
| **RegDataSetInDataStore** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
