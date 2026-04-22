---
title: "StiDataStoreSource Class"
---

## StiDataStoreSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public abstract class StiDataStoreSource
```

### Inheritance

Inherits from: StiDataSource  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataStoreSource**() | Creates a new object of the type StiDataStoreSource. |
| **StiDataStoreSource**(string nameInSource, string name) | Creates a new object of the type StiDataTableSource. |
| **StiDataStoreSource**(string nameInSource, string name, string alias) | Creates a new object of the type StiDataStoreSource. |
| **StiDataStoreSource**(string nameInSource, string name, string alias, string key) | Creates a new object of the type StiDataStoreSource. |
| **StiDataStoreSource**(string nameInSource, string name, string alias, string key, bool reconnectOnEachRow) | Creates a new object of the type StiDataStoreSource. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **NameInSource** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetCategoryName** | string | Returns the name to categories of the Data Source. |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
