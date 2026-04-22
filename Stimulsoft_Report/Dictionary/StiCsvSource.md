---
title: "StiCsvSource Class"
---

## StiCsvSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiCsvSource
```

### Inheritance

Inherits from: [StiFileDataSource](StiFileDataSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiCsvSource()` | Creates a new object of the type StiCsvSource. |
| `StiCsvSource(string path, string name, string alias, int codePage)` |  |
| `StiCsvSource(string path, string name, string alias, int codePage, string separator)` |  |
| `StiCsvSource(string path, string name, string alias, int codePage, string separator, string key)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ConvertEmptyStringToNull** | bool |  |
| **Separator** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDataAdapterType** | Type |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
