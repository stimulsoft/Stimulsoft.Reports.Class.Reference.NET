---
title: "TimeSpanRange Class"
---

## TimeSpanRange Class

**Namespace:** `Stimulsoft.Report`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class TimeSpanRange
```

### Inheritance

Inherits from: [Range](Range.md)  
Implements: IComparable  

### Constructors

| Constructor | Description |
| --- | --- |
| `TimeSpanRange()` |  |
| `TimeSpanRange(TimeSpan from, TimeSpan to)` |  |
| `TimeSpanRange(TimeSpan? from, TimeSpan? to)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** *(+1 overloads)* | bool |  |
| **Parse** | void | Fill From and To item of range with it string representation. |
| **ToString** | string |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **From** | TimeSpan? |  |
| **FromTime** | TimeSpan |  |
| **To** | TimeSpan? |  |
| **ToTime** | TimeSpan |  |
