---
title: "StiPagesRange Class"
---

## StiPagesRange Class

**Namespace:** `Stimulsoft.Report`  
**Assembly:** `Stimulsoft.Report`

```csharp
public sealed class StiPagesRange
```

### Constructors

| Constructor | Description |
| --- | --- |
| `StiPagesRange()` | Creates a new instance of the StiPagesRange class. |
| `StiPagesRange(int currentPage)` | Creates a new instance of the StiPagesRange class. |
| `StiPagesRange(string pageRanges)` | Creates a new instance of the StiPagesRange class. |
| `StiPagesRange([StiRangeType](StiRangeType.md) rangeType, string pageRanges, int currentPage)` | Creates a new instance of the StiPagesRange class. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CurrentPage** | int |  |
| **PageRanges** | string |  |
| **RangeType** | [StiRangeType](StiRangeType.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Equals** | bool |  |
| **GetHashCode** | int |  |
| **GetSelectedPages** | [StiPagesCollection](Components/StiPagesCollection.md) | Returns collection of selected pages. |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **All** | [StiPagesRange](StiPagesRange.md) |  |
