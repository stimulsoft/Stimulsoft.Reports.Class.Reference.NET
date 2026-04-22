---
title: "PointD Struct"
---

## PointD Struct

**Namespace:** `Stimulsoft.Base.Drawing`  
**Assembly:** `Stimulsoft.Base`

```csharp
public struct PointD
```

### Constructors

| Constructor | Description |
| --- | --- |
| `PointD(double x, double y)` | Initializes a new instance of the PointD class with the specified coordinates. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **X** | double | Gets or sets the x-coordinate of this PointD. |
| **Y** | double | Gets or sets the y-coordinate of this PointD. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Equals** | bool | Specifies whether this PointD contains the same coordinates as the specified Object. |
| **GetHashCode** | int | Returns a hash code for this PointD structure. |
| **ToPoint** | Point |  |
| **ToPointF** | PointF |  |
| **ToString** | string | Converts this PointD to a human readable string. |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Empty** | [PointD](PointD.md) | Represents a null PointD. |
| **IsEmpty** | bool |  |
