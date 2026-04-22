---
title: "StiGisRect Struct"
---

## StiGisRect Struct

**Namespace:** `Stimulsoft.Map.Gis.Core`  
**Assembly:** `Stimulsoft.Map`

```csharp
public struct StiGisRect
```

### Constructors

| Constructor | Description |
| --- | --- |
| `StiGisRect([StiGisPoint](StiGisPoint.md) location, [StiGisSize](StiGisSize.md) size)` |  |
| `StiGisRect(int x, int y, int width, int height)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Height** | int |  |
| **Width** | int |  |
| **X** | int |  |
| **Y** | int |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** *(+2 overloads)* | bool |  |
| **Equals** | bool |  |
| **GetHashCode** | int |  |
| **Inflate** | void |  |
| **Offset** | void |  |
| **OffsetNegative** | void |  |
| **ToString** | string |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Bottom** | int |  |
| **Empty** | [StiGisRect](StiGisRect.md) |  |
| **IsEmpty** | bool |  |
| **Left** | int |  |
| **LeftBottom** | [StiGisPoint](StiGisPoint.md) |  |
| **Right** | int |  |
| **RightBottom** | [StiGisPoint](StiGisPoint.md) |  |
| **RightTop** | [StiGisPoint](StiGisPoint.md) |  |
| **Top** | int |  |
