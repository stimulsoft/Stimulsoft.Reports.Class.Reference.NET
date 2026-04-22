---
title: "StiDataTableSource Class"
---

## StiDataTableSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

Describes the Data Source realizing access to DataTable.

```csharp
public class StiDataTableSource
```

### Inheritance

Inherits from: [StiDataStoreSource](StiDataStoreSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiDataTableSource()` | Creates a new object of the type StiDataTableSource. |
| `StiDataTableSource(string nameInSource, string name)` | Creates a new object of the type StiDataTableSource. |
| `StiDataTableSource(string nameInSource, string name, string alias)` | Creates a new object of the type StiDataTableSource. |
| `StiDataTableSource(string nameInSource, string name, string alias, string key)` | Creates a new object of the type StiDataTableSource. |
| `StiDataTableSource(string nameInSource, string name, string alias, string key, bool reconnectOnEachRow)` | Creates a new object of the type StiDataTableSource. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetCategoryName** | string |  |
| **GetDataAdapterType** | Type |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
