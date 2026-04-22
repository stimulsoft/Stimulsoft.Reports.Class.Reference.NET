---
title: "StiAppsColumn Class"
---

## StiAppsColumn Class

**Namespace:** `Stimulsoft.Base.AppsDatabase`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiAppsColumn
```

### Constructors

| Constructor | Description |
| --- | --- |
| `StiAppsColumn()` |  |
| `StiAppsColumn(string name, [StiAppsColumnType](StiAppsColumnType.md) type)` |  |
| `StiAppsColumn(string name, [StiAppsColumnType](StiAppsColumnType.md) type, bool isNull)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DefaultValue** | object |  |
| **Description** | string |  |
| **IsNull** | bool |  |
| **IsSystem** | bool |  |
| **Name** | string | Gets or sets a name of the table column. |
| **Size** | int? |  |
| **Type** | [StiAppsColumnType](StiAppsColumnType.md) | Get or sets a type of the table column. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConvertTypeToDataColumnType** | Type |  |
| **ToString** | string |  |
