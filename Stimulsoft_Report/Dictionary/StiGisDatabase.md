---
title: "StiGisDatabase Class"
---

## StiGisDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiGisDatabase
```

### Inheritance

Inherits from: [StiFileDatabase](StiFileDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGisDatabase**() |  |
| **StiGisDatabase**(string name, string pathData) |  |
| **StiGisDatabase**(string name, string pathData, string key) |  |
| **StiGisDatabase**(string name, string pathData, string key, [StiGisDataType](../../Stimulsoft_Base/StiGisDataType.md) dataType) |  |
| **StiGisDatabase**(string name, string pathData, string key, [StiGisDataType](../../Stimulsoft_Base/StiGisDataType.md) dataType, [StiColumnTypeProcessing](StiColumnTypeProcessing.md) castToColumnType) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DataType** | [StiGisDataType](../../Stimulsoft_Base/StiGisDataType.md) |  |
| **Separator** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CopyDataSourceFrom** | StiDataSource |  |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/StiDataConnector.md) | Returns new data connector for this database. |
| **Edit** | DialogResult |  |
| **EditAsync** | Task<DialogResult> |  |
| **GetConnectorOptions** | [StiFileDataOptions](../../Stimulsoft_Base/StiFileDataOptions.md) |  |
| **GetNestedResources** | List<StiResource> | Returns a list of the resources which connected to this database. |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
