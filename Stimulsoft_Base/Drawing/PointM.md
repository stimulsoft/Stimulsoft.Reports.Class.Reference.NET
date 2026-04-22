---
title: "PointM Struct"
---

## PointM Struct

**Namespace:** `Stimulsoft.Base.Drawing`  
**Assembly:** `Stimulsoft.Base`

```csharp
public struct PointM
```

### Constructors

| Constructor | Description |
| --- | --- |
| `PointM(decimal x, decimal y)` | Initializes a new instance of the PointM class with the specified coordinates. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **X** | decimal | Gets or sets the x-coordinate of this PointM. |
| **Y** | decimal | Gets or sets the y-coordinate of this PointM. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Equals** | bool | Specifies whether this PointM contains the same coordinates as the specified Object. |
| **GetHashCode** | int | Returns a hash code for this PointM structure. |
| **ToPoint** | Point |  |
| **ToPointD** | [PointD](PointD.md) |  |
| **ToPointF** | PointF |  |
| **ToString** | string | Converts this PointM to a human readable string. |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Empty** | [PointM](PointM.md) | Represents a null PointM. |
| **IsEmpty** | bool |  |
