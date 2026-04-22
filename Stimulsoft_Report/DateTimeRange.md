---
title: "DateTimeRange Class"
---

## DateTimeRange Class

**Namespace:** `Stimulsoft.Report`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class DateTimeRange
```

### Inheritance

Inherits from: [Range](Range.md)  
Implements: IComparable  

### Constructors

| Constructor | Description |
| --- | --- |
| `DateTimeRange()` |  |
| `DateTimeRange(DateTime from, DateTime to)` |  |
| `DateTimeRange(DateTime? from, DateTime? to)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** *(+1 overloads)* | bool |  |
| **Parse** | void | Fill From and To item of range with it string representation. |
| **ToString** *(+1 overloads)* | string |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **From** | DateTime? |  |
| **FromDate** | DateTime |  |
| **To** | DateTime? |  |
| **ToDate** | DateTime |  |
