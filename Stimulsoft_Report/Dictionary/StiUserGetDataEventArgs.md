---
title: "StiUserGetDataEventArgs Class"
---

## StiUserGetDataEventArgs Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

Class describes the arguments for event StiUserGetDataEvent.

```csharp
public class StiUserGetDataEventArgs
```

### Constructors

| Constructor | Description |
| --- | --- |
| `StiUserGetDataEventArgs([StiUserSource](StiUserSource.md) userSource, int position, string columnName)` | Creates a new object of the type StiUserGetDataEventArgs. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ColumnName** | string | Gets name of the column with data. |
| **Data** | object | Gets or sets data. |
| **Position** | int | Gets current position in data. |
| **UserSource** | [StiUserSource](StiUserSource.md) | Gets user source. |
