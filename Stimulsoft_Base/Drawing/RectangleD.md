---
title: "RectangleD Struct"
---

## RectangleD Struct

**Namespace:** `Stimulsoft.Base.Drawing`  
**Assembly:** `Stimulsoft.Base`

```csharp
public struct RectangleD
```

### Constructors

| Constructor | Description |
| --- | --- |
| `RectangleD([PointD](PointD.md) location, [SizeD](SizeD.md) size)` | Initializes a new instance of the RectangleD class with the specified location and size. |
| `RectangleD(double x, double y, double width, double height)` | Initializes a new instance of the RectangleD class with the specified location and size. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Height** | double | Gets or sets the height of this RectangleD structure. |
| **Width** | double | Gets or sets the width of this RectangleD structure. |
| **X** | double | Gets or sets the x-coordinate of the upper-left corner of this RectangleD structure. |
| **Y** | double | Gets or sets the y-coordinate of the upper-left corner of this RectangleD structure. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AlignToGrid** | [RectangleD](RectangleD.md) | Align the rectangle to grid. |
| **Ceiling** `static` | [RectangleD](RectangleD.md) |  |
| **Contains** *(+2 overloads)* | bool | Determines if the specified point is contained within this RectangleD structure. |
| **CreateFromRectangle** `static` *(+1 overloads)* | [RectangleD](RectangleD.md) | Creates the specified RectangleD from a Rectangle. |
| **Divide** | [RectangleD](RectangleD.md) | Divides rectangle on number. |
| **Equals** | bool | Tests whether obj is a RectangleF with the same location and size of this RectangleD. |
| **FitToRectangle** | [RectangleD](RectangleD.md) | Fit rectangle to rectangle. |
| **GetHashCode** | int | Returns a hash code for this RectangleD structure. |
| **Inflate** | void |  |
| **Intersect** `static` *(+1 overloads)* | [RectangleD](RectangleD.md) |  |
| **IntersectsWith** | bool | Determines if this rectangle intersects with rect. |
| **LoadFromJson** | void |  |
| **Multiply** | [RectangleD](RectangleD.md) | Multiplies the rectangle on number. |
| **Normalize** | [RectangleD](RectangleD.md) | Normalizes (convert all negative values) rectangle. |
| **OffsetRect** | [RectangleD](RectangleD.md) | Changes the sizes of the rectangle. |
| **OffsetSize** | [RectangleD](RectangleD.md) | Changes the sizes of the rectangle. |
| **Round** `static` | [RectangleD](RectangleD.md) |  |
| **ToRectangle** | Rectangle | Converts the specified RectangleD to a Rectangle. |
| **ToRectangleF** | RectangleF | Converts the specified RectangleD to a RectangleF. |
| **ToRectangleM** | [RectangleM](RectangleM.md) |  |
| **ToString** | string |  |
| **Union** `static` | [RectangleD](RectangleD.md) |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Bottom** | double | Gets the y-coordinate of the bottom edge of this RectangleD structure. |
| **Empty** | [RectangleD](RectangleD.md) | Represents an instance of the RectangleD class with its members uninitialized. |
| **IsEmpty** | bool | Tests whether all numeric properties of this RectangleD have values of zero. |
| **Left** | double | Gets or sets the x-coordinate of the upper-left corner of this RectangleD structure. |
| **Location** | [PointD](PointD.md) | Gets or sets the coordinates of the upper-left corner of this RectangleD structure. |
| **Right** | double | Gets the x-coordinate of the right edge of this RectangleD structure. |
| **Size** | [SizeD](SizeD.md) | Gets or sets the size of this RectangleD. |
| **Top** | double | Gets or sets the y-coordinate of the upper-left corner of this RectangleD structure. |
