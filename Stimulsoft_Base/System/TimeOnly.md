---
title: "TimeOnly Struct"
---

## TimeOnly Struct

**Namespace:** `System`  
**Assembly:** `Stimulsoft.Base`

```csharp
public struct TimeOnly
```

### Inheritance

Implements: IComparable  

### Constructors

| Constructor | Description |
| --- | --- |
| `TimeOnly(long ticks)` |  |
| `TimeOnly(DateTime dateTime)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Equals** | bool |  |
| **FromDateTime** `static` | [TimeOnly](TimeOnly.md) |  |
| **GetHashCode** | int |  |
| **Parse** `static` *(+2 overloads)* | [TimeOnly](TimeOnly.md) |  |
| **ToString** *(+3 overloads)* | string |  |
| **TryParse** `static` *(+2 overloads)* | bool |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Hour** | int |  |
| **Millisecond** | int |  |
| **Minute** | int |  |
| **Second** | int |  |
| **Zero** | [TimeOnly](TimeOnly.md) |  |
