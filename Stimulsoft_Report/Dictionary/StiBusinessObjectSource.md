---
title: "StiBusinessObjectSource Class"
---

## StiBusinessObjectSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

Describes the Data Source realizing access to Business Objects.

```csharp
public class StiBusinessObjectSource
```

### Inheritance

Inherits from: [StiDataTableSource](StiDataTableSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiBusinessObjectSource**() | Creates a new object of the type StiBusinessObjectSource. |
| **StiBusinessObjectSource**(string nameInSource, string name) | Creates a new object of the type StiBusinessObjectSource. |
| **StiBusinessObjectSource**(string nameInSource, string name, string alias) | Creates a new object of the type StiBusinessObjectSource. |
| **StiBusinessObjectSource**(string nameInSource, string name, string alias, string key) | Creates a new object of the type StiBusinessObjectSource. |
| **StiBusinessObjectSource**(string nameInSource, string name, string alias, string key, bool reconnectOnEachRow) | Creates a new object of the type StiBusinessObjectSource. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetCategoryName** | string | Returns the name to categories of the Data Source. |
| **GetDataAdapterType** | Type |  |
