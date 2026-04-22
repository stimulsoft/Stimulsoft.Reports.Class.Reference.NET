---
title: "Range Class"
---

## Range Class

**Namespace:** `Stimulsoft.Report`  
**Assembly:** `Stimulsoft.Report`

```csharp
public abstract class Range
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **FromObject** | object | Gets or sets From item of range. |
| **RangeName** | string | Gets specified name of range. Range name equal to name of range class. |
| **RangeType** | Type | Gets the type of range items. |
| **ToObject** | object | Gets or set To item of range. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Equals** | bool |  |
| **GetHashCode** | int |  |
| **IsRangeType** `static` | bool |  |
| **Parse** | void | Fill From and To item of range with it string representation. |
| **ToDecimalRange** | [DecimalRange](DecimalRange.md) |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **FromStrLoc** | string |  |
| **ToStrLoc** | string |  |
