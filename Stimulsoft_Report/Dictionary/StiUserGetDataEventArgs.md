---
title: "StiUserGetDataEventArgs Class"
---

## StiUserGetDataEventArgs Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Class describes the arguments for event StiUserGetDataEvent.

### Constructors

| Constructor | Description |
| --- | --- |
| **StiUserGetDataEventArgs**([StiUserSource](StiUserSource.md) userSource, int position, string columnName) | Creates a new object of the type StiUserGetDataEventArgs. |

**StiUserGetDataEventArgs**(**userSource**: [StiUserSource](StiUserSource.md), **position**: int, **columnName**: string)

Creates a new object of the type StiUserGetDataEventArgs.

**Parameters**

- **userSource** ([StiUserSource](StiUserSource.md)) — Data source.  
- **position** (int) — Current position in data.  
- **columnName** (string) — Name of the column with data.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ColumnName** | string | Gets name of the column with data. |
| **Data** | object | Gets or sets data. |
| **Position** | int | Gets current position in data. |
| **UserSource** | [StiUserSource](StiUserSource.md) | Gets user source. |
