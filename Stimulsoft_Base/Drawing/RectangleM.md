---
title: "RectangleM Struct"
---

## RectangleM Struct

**Namespace:** `Stimulsoft.Base.Drawing`

### Constructors

| Constructor | Description |
| --- | --- |
| **RectangleM**([PointM](PointM.md) location, [SizeM](SizeM.md) size) | Initializes a new instance of the RectangleM class with the specified location and size. |
| **RectangleM**(decimal x, decimal y, decimal width, decimal height) | Initializes a new instance of the RectangleM class with the specified location and size. |

**RectangleM**(**location**: [PointM](PointM.md), **size**: [SizeM](SizeM.md))

Initializes a new instance of the RectangleM class with the specified location and size.

**Parameters**

- **location** ([PointM](PointM.md)) — A PointM that represents the upper-left corner of the rectangular region.  
- **size** ([SizeM](SizeM.md)) — A SizeM that represents the width and height of the rectangular region.  

---

**RectangleM**(**x**: decimal, **y**: decimal, **width**: decimal, **height**: decimal)

Initializes a new instance of the RectangleM class with the specified location and size.

**Parameters**

- **x** (decimal) — The x-coordinate of the upper-left corner of the rectangle.  
- **y** (decimal) — The y-coordinate of the upper-left corner of the rectangle.  
- **width** (decimal) — The width of the rectangle.  
- **height** (decimal) — The height of the rectangle.  


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

---

### Method Details

#### AlignToGrid

**AlignToGrid**(**gridSize**: decimal, **aligningToGrid**: bool): [RectangleM](RectangleM.md)

Align the rectangle to grid.

**Parameters**

- **gridSize** (decimal) — Grid size.  
- **aligningToGrid** (bool) — Align or no.  

**Returns** [RectangleM](RectangleM.md) — Aligned rectangle.


---

#### Contains

**Contains**(**pt**: [PointM](PointM.md)): bool

Determines if the specified point is contained within this RectangleM structure.

**Parameters**

- **pt** ([PointM](PointM.md)) — The PointM to test.  

**Returns** bool — This method returns true if the point represented by the pt parameter is contained within this RectangleM structure; otherwise false.

---

**Contains**(**rect**: [RectangleM](RectangleM.md)): bool

Determines if the rectangular region represented by rect is entirely contained within this RectangleM structure.

**Parameters**

- **rect** ([RectangleM](RectangleM.md)) — The RectangleM to test.  

**Returns** bool — This method returns true if the rectangular region represented by rect is entirely contained within the rectangular region represented by this RectangleM; otherwise false.

---

**Contains**(**x**: decimal, **y**: decimal): bool

Determines if the specified point is contained within this RectangleM structure.

**Parameters**

- **x** (decimal) — The x-coordinate of the point to test.  
- **y** (decimal) — The y-coordinate of the point to test.  

**Returns** bool — This method returns true if the point defined by x and y is contained within this RectangleM structure; otherwise false.


---

#### CreateFromRectangle `static`

**CreateFromRectangle**(**rect**: Rectangle): [RectangleM](RectangleM.md)

Creates the specified RectangleM from a Rectangle.

**Parameters**

- **rect** (Rectangle)  

**Returns** [RectangleM](RectangleM.md)

---

**CreateFromRectangle**(**rect**: RectangleF): [RectangleM](RectangleM.md)

Creates the specified RectangleM from a RectangleF.

**Parameters**

- **rect** (RectangleF)  

**Returns** [RectangleM](RectangleM.md)


---

#### Divide

**Divide**(**divideFactor**: decimal): [RectangleM](RectangleM.md)

Divides rectangle on number.

**Parameters**

- **divideFactor** (decimal) — Number.  

**Returns** [RectangleM](RectangleM.md) — Divided rectangle.


---

#### Equals

**Equals**(**obj**: object): bool

Tests whether obj is a RectangleF with the same location and size of this RectangleM.

**Parameters**

- **obj** (object) — The Object to test.  

**Returns** bool — This method returns true if obj is a RectangleM and its X, Y, Width, and Height properties are equal to the corresponding properties of this RectangleM; otherwise, false.


---

#### FitToRectangle

**FitToRectangle**(**rectangle**: [RectangleM](RectangleM.md)): [RectangleM](RectangleM.md)

Fit rectangle to rectangle.

**Parameters**

- **rectangle** ([RectangleM](RectangleM.md)) — Rectangle, which will be fited.  

**Returns** [RectangleM](RectangleM.md) — Result rectangle.


---

#### GetHashCode

**GetHashCode**(): int

Returns a hash code for this RectangleM structure.

**Returns** int — An integer value that specifies a hash value for this RectangleM structure.


---

#### Inflate

**Inflate**(**width**: decimal, **height**: decimal): void

**Parameters**

- **width** (decimal)  
- **height** (decimal)  


---

#### Intersect `static`

**Intersect**(**a**: [RectangleM](RectangleM.md), **b**: [RectangleM](RectangleM.md)): [RectangleM](RectangleM.md)

**Parameters**

- **a** ([RectangleM](RectangleM.md))  
- **b** ([RectangleM](RectangleM.md))  

**Returns** [RectangleM](RectangleM.md)

---

**Intersect**(**rect**: [RectangleM](RectangleM.md)): void

**Parameters**

- **rect** ([RectangleM](RectangleM.md))  


---

#### IntersectsWith

**IntersectsWith**(**rect**: [RectangleM](RectangleM.md)): bool

Determines if this rectangle intersects with rect.

**Parameters**

- **rect** ([RectangleM](RectangleM.md))  

**Returns** bool


---

#### LoadFromJson

**LoadFromJson**(**jObject**: [JObject](../Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../Json/Linq/JObject.md))  


---

#### Multiply

**Multiply**(**multipleFactor**: decimal): [RectangleM](RectangleM.md)

Multiplies the rectangle on number.

**Parameters**

- **multipleFactor** (decimal) — Number.  

**Returns** [RectangleM](RectangleM.md) — Multiplied rectangle.


---

#### Normalize

**Normalize**(): [RectangleM](RectangleM.md)

Normalizes (convert all negative values) rectangle.

**Returns** [RectangleM](RectangleM.md) — Normalized rectangle.


---

#### OffsetRect

**OffsetRect**(**offsettingRectangle**: [RectangleM](RectangleM.md)): [RectangleM](RectangleM.md)

Changes the sizes of the rectangle.

**Parameters**

- **offsettingRectangle** ([RectangleM](RectangleM.md)) — Data for change the size.  

**Returns** [RectangleM](RectangleM.md) — Changed rectangle.


---

#### OffsetSize

**OffsetSize**(**offsettingRectangle**: [RectangleM](RectangleM.md)): [RectangleM](RectangleM.md)

Changes the sizes of the rectangle.

**Parameters**

- **offsettingRectangle** ([RectangleM](RectangleM.md)) — Data for change the size.  

**Returns** [RectangleM](RectangleM.md) — Changed rectangle.


---

#### ToRectangle

**ToRectangle**(): Rectangle

Converts the specified RectangleM to a Rectangle.

**Returns** Rectangle


---

#### ToRectangleD

**ToRectangleD**(): [RectangleD](RectangleD.md)

Converts the specified RectangleM to a RectangleD.

**Returns** [RectangleD](RectangleD.md)


---

#### ToRectangleF

**ToRectangleF**(): RectangleF

Converts the specified RectangleM to a RectangleF.

**Returns** RectangleF


---

#### ToString

**ToString**(): string

**Returns** string


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
