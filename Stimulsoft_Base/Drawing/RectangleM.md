---
title: "RectangleM Struct"
---

## RectangleM Struct

**Namespace:** `Stimulsoft.Base.Drawing`  
**Assembly:** `Stimulsoft.Base`

```csharp
public struct RectangleM
```

### Constructors

| Constructor | Description |
| --- | --- |
| **RectangleM**([PointM](PointM.md) location, [SizeM](SizeM.md) size) | Initializes a new instance of the RectangleM class with the specified location and size. |
| **RectangleM**(decimal x, decimal y, decimal width, decimal height) | Initializes a new instance of the RectangleM class with the specified location and size. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Height** | decimal | Gets or sets the height of this RectangleM structure. |
| **Width** | decimal | Gets or sets the width of this RectangleM structure. |
| **X** | decimal | Gets or sets the x-coordinate of the upper-left corner of this RectangleM structure. |
| **Y** | decimal | Gets or sets the y-coordinate of the upper-left corner of this RectangleM structure. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AlignToGrid** | [RectangleM](RectangleM.md) | Align the rectangle to grid. |
| **Contains** *(+2 overloads)* | bool | Determines if the specified point is contained within this RectangleM structure. |
| **CreateFromRectangle** `static` *(+1 overloads)* | [RectangleM](RectangleM.md) | Creates the specified RectangleM from a Rectangle. |
| **Divide** | [RectangleM](RectangleM.md) | Divides rectangle on number. |
| **Equals** | bool | Tests whether obj is a RectangleF with the same location and size of this RectangleM. |
| **FitToRectangle** | [RectangleM](RectangleM.md) | Fit rectangle to rectangle. |
| **GetHashCode** | int | Returns a hash code for this RectangleM structure. |
| **Inflate** | void |  |
| **Intersect** `static` *(+1 overloads)* | [RectangleM](RectangleM.md) |  |
| **IntersectsWith** | bool | Determines if this rectangle intersects with rect. |
| **LoadFromJson** | void |  |
| **Multiply** | [RectangleM](RectangleM.md) | Multiplies the rectangle on number. |
| **Normalize** | [RectangleM](RectangleM.md) | Normalizes (convert all negative values) rectangle. |
| **OffsetRect** | [RectangleM](RectangleM.md) | Changes the sizes of the rectangle. |
| **OffsetSize** | [RectangleM](RectangleM.md) | Changes the sizes of the rectangle. |
| **ToRectangle** | Rectangle | Converts the specified RectangleM to a Rectangle. |
| **ToRectangleD** | [RectangleD](RectangleD.md) | Converts the specified RectangleM to a RectangleD. |
| **ToRectangleF** | RectangleF | Converts the specified RectangleM to a RectangleF. |
| **ToString** | string |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Bottom** | decimal | Gets the y-coordinate of the bottom edge of this RectangleM structure. |
| **Empty** | [RectangleM](RectangleM.md) | Represents an instance of the RectangleM class with its members uninitialized. |
| **IsEmpty** | bool | Tests whether all numeric properties of this RectangleM have values of zero. |
| **Left** | decimal | Gets or sets the x-coordinate of the upper-left corner of this RectangleM structure. |
| **Location** | [PointM](PointM.md) | Gets or sets the coordinates of the upper-left corner of this RectangleM structure. |
| **Right** | decimal | Gets the x-coordinate of the right edge of this RectangleM structure. |
| **Size** | [SizeM](SizeM.md) | Gets or sets the size of this RectangleM. |
| **Top** | decimal | Gets or sets the y-coordinate of the upper-left corner of this RectangleM structure. |
