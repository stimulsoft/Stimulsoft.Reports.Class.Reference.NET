---
title: "PointD Struct"
---

## PointD Struct

**Namespace:** `Stimulsoft.Base.Drawing`

### Constructors

| Constructor | Description |
| --- | --- |
| **PointD**(double x, double y) | Initializes a new instance of the PointD class with the specified coordinates. |

**PointD**(**x**: double, **y**: double)

Initializes a new instance of the PointD class with the specified coordinates.

**Parameters**

- **x** (double) — The horizontal position of the point.  
- **y** (double) — The vertical position of the point.  


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

---

### Method Details

#### Equals

**Equals**(**obj**: object): bool

Specifies whether this PointD contains the same coordinates as the specified Object.

**Parameters**

- **obj** (object) — The Object to test.  

**Returns** bool — This method returns true if obj is a PointD and has the same coordinates as this Point.


---

#### GetHashCode

**GetHashCode**(): int

Returns a hash code for this PointD structure.

**Returns** int — An integer value that specifies a hash value for this PointD structure.


---

#### ToPoint

**ToPoint**(): Point

**Returns** Point


---

#### ToPointF

**ToPointF**(): PointF

**Returns** PointF


---

#### ToString

**ToString**(): string

Converts this PointD to a human readable string.

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Empty** | [PointD](PointD.md) | Represents a null PointD. |
| **IsEmpty** | bool |  |
