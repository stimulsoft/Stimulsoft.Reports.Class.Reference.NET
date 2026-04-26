---
title: "RectangleD Struct"
---

## RectangleD Struct

**Namespace:** `Stimulsoft.Base.Drawing`

### Constructors

| Constructor | Description |
| --- | --- |
| **RectangleD**([PointD](PointD.md) location, [SizeD](SizeD.md) size) | Initializes a new instance of the RectangleD class with the specified location and size. |
| **RectangleD**(double x, double y, double width, double height) | Initializes a new instance of the RectangleD class with the specified location and size. |

**RectangleD**(**location**: [PointD](PointD.md), **size**: [SizeD](SizeD.md))

Initializes a new instance of the RectangleD class with the specified location and size.

**Parameters**

- **location** ([PointD](PointD.md)) — A PointD that represents the upper-left corner of the rectangular region.  
- **size** ([SizeD](SizeD.md)) — A SizeD that represents the width and height of the rectangular region.  

---

**RectangleD**(**x**: double, **y**: double, **width**: double, **height**: double)

Initializes a new instance of the RectangleD class with the specified location and size.

**Parameters**

- **x** (double) — The x-coordinate of the upper-left corner of the rectangle.  
- **y** (double) — The y-coordinate of the upper-left corner of the rectangle.  
- **width** (double) — The width of the rectangle.  
- **height** (double) — The height of the rectangle.  


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

---

### Method Details

#### AlignToGrid

**AlignToGrid**(**gridSize**: double, **aligningToGrid**: bool): [RectangleD](RectangleD.md)

Align the rectangle to grid.

**Parameters**

- **gridSize** (double) — Grid size.  
- **aligningToGrid** (bool) — Align or no.  

**Returns** [RectangleD](RectangleD.md) — Aligned rectangle.


---

#### Ceiling `static`

**Ceiling**(**value**: [RectangleD](RectangleD.md)): [RectangleD](RectangleD.md)

**Parameters**

- **value** ([RectangleD](RectangleD.md))  

**Returns** [RectangleD](RectangleD.md)


---

#### Contains

**Contains**(**pt**: [PointD](PointD.md)): bool

Determines if the specified point is contained within this RectangleD structure.

**Parameters**

- **pt** ([PointD](PointD.md)) — The PointD to test.  

**Returns** bool — This method returns true if the point represented by the pt parameter is contained within this RectangleD structure; otherwise false.

---

**Contains**(**rect**: [RectangleD](RectangleD.md)): bool

Determines if the rectangular region represented by rect is entirely contained within this RectangleD structure.

**Parameters**

- **rect** ([RectangleD](RectangleD.md)) — The RectangleD to test.  

**Returns** bool — This method returns true if the rectangular region represented by rect is entirely contained within the rectangular region represented by this RectangleD; otherwise false.

---

**Contains**(**x**: double, **y**: double): bool

Determines if the specified point is contained within this RectangleD structure.

**Parameters**

- **x** (double) — The x-coordinate of the point to test.  
- **y** (double) — The y-coordinate of the point to test.  

**Returns** bool — This method returns true if the point defined by x and y is contained within this RectangleD structure; otherwise false.


---

#### CreateFromRectangle `static`

**CreateFromRectangle**(**rect**: Rectangle): [RectangleD](RectangleD.md)

Creates the specified RectangleD from a Rectangle.

**Parameters**

- **rect** (Rectangle)  

**Returns** [RectangleD](RectangleD.md)

---

**CreateFromRectangle**(**rect**: RectangleF): [RectangleD](RectangleD.md)

Creates the specified RectangleD from a RectangleF.

**Parameters**

- **rect** (RectangleF)  

**Returns** [RectangleD](RectangleD.md)


---

#### Divide

**Divide**(**divideFactor**: double): [RectangleD](RectangleD.md)

Divides rectangle on number.

**Parameters**

- **divideFactor** (double) — Number.  

**Returns** [RectangleD](RectangleD.md) — Divided rectangle.


---

#### Equals

**Equals**(**obj**: object): bool

Tests whether obj is a RectangleF with the same location and size of this RectangleD.

**Parameters**

- **obj** (object) — The Object to test.  

**Returns** bool — This method returns true if obj is a RectangleD and its X, Y, Width, and Height properties are equal to the corresponding properties of this RectangleD; otherwise, false.


---

#### FitToRectangle

**FitToRectangle**(**rectangle**: [RectangleD](RectangleD.md)): [RectangleD](RectangleD.md)

Fit rectangle to rectangle.

**Parameters**

- **rectangle** ([RectangleD](RectangleD.md)) — Rectangle, which will be fited.  

**Returns** [RectangleD](RectangleD.md) — Result rectangle.


---

#### GetHashCode

**GetHashCode**(): int

Returns a hash code for this RectangleD structure.

**Returns** int — An integer value that specifies a hash value for this RectangleD structure.


---

#### Inflate

**Inflate**(**width**: double, **height**: double): void

**Parameters**

- **width** (double)  
- **height** (double)  


---

#### Intersect `static`

**Intersect**(**a**: [RectangleD](RectangleD.md), **b**: [RectangleD](RectangleD.md)): [RectangleD](RectangleD.md)

**Parameters**

- **a** ([RectangleD](RectangleD.md))  
- **b** ([RectangleD](RectangleD.md))  

**Returns** [RectangleD](RectangleD.md)

---

**Intersect**(**rect**: [RectangleD](RectangleD.md)): void

**Parameters**

- **rect** ([RectangleD](RectangleD.md))  


---

#### IntersectsWith

**IntersectsWith**(**rect**: [RectangleD](RectangleD.md)): bool

Determines if this rectangle intersects with rect.

**Parameters**

- **rect** ([RectangleD](RectangleD.md))  

**Returns** bool


---

#### LoadFromJson

**LoadFromJson**(**jObject**: [JObject](../Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../Json/Linq/JObject.md))  


---

#### Multiply

**Multiply**(**multipleFactor**: double): [RectangleD](RectangleD.md)

Multiplies the rectangle on number.

**Parameters**

- **multipleFactor** (double) — Number.  

**Returns** [RectangleD](RectangleD.md) — Multiplied rectangle.


---

#### Normalize

**Normalize**(): [RectangleD](RectangleD.md)

Normalizes (convert all negative values) rectangle.

**Returns** [RectangleD](RectangleD.md) — Normalized rectangle.


---

#### OffsetRect

**OffsetRect**(**offsettingRectangle**: [RectangleD](RectangleD.md)): [RectangleD](RectangleD.md)

Changes the sizes of the rectangle.

**Parameters**

- **offsettingRectangle** ([RectangleD](RectangleD.md)) — Data for change the size.  

**Returns** [RectangleD](RectangleD.md) — Changed rectangle.


---

#### OffsetSize

**OffsetSize**(**offsettingRectangle**: [RectangleD](RectangleD.md)): [RectangleD](RectangleD.md)

Changes the sizes of the rectangle.

**Parameters**

- **offsettingRectangle** ([RectangleD](RectangleD.md)) — Data for change the size.  

**Returns** [RectangleD](RectangleD.md) — Changed rectangle.


---

#### Round `static`

**Round**(**value**: [RectangleD](RectangleD.md)): [RectangleD](RectangleD.md)

**Parameters**

- **value** ([RectangleD](RectangleD.md))  

**Returns** [RectangleD](RectangleD.md)


---

#### ToRectangle

**ToRectangle**(): Rectangle

Converts the specified RectangleD to a Rectangle.

**Returns** Rectangle


---

#### ToRectangleF

**ToRectangleF**(): RectangleF

Converts the specified RectangleD to a RectangleF.

**Returns** RectangleF


---

#### ToRectangleM

**ToRectangleM**(): [RectangleM](RectangleM.md)

**Returns** [RectangleM](RectangleM.md)


---

#### ToString

**ToString**(): string

**Returns** string


---

#### Union `static`

**Union**(**a**: [RectangleD](RectangleD.md), **b**: [RectangleD](RectangleD.md)): [RectangleD](RectangleD.md)

**Parameters**

- **a** ([RectangleD](RectangleD.md))  
- **b** ([RectangleD](RectangleD.md))  

**Returns** [RectangleD](RectangleD.md)


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
