---
title: "PointM Struct"
---

## PointM Struct

**Namespace:** `Stimulsoft.Base.Drawing`

### Constructors

| Constructor | Description |
| --- | --- |
| **PointM**(decimal x, decimal y) | Initializes a new instance of the PointM class with the specified coordinates. |

**PointM**(**x**: decimal, **y**: decimal)

Initializes a new instance of the PointM class with the specified coordinates.

**Parameters**

- **x** (decimal) — The horizontal position of the point.  
- **y** (decimal) — The vertical position of the point.  


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

---

### Method Details

#### Equals

**Equals**(**obj**: object): bool

Specifies whether this PointM contains the same coordinates as the specified Object.

**Parameters**

- **obj** (object) — The Object to test.  

**Returns** bool — This method returns true if obj is a PointM and has the same coordinates as this Point.


---

#### GetHashCode

**GetHashCode**(): int

Returns a hash code for this PointM structure.

**Returns** int — An integer value that specifies a hash value for this PointM structure.


---

#### ToPoint

**ToPoint**(): Point

**Returns** Point


---

#### ToPointD

**ToPointD**(): [PointD](PointD.md)

**Returns** [PointD](PointD.md)


---

#### ToPointF

**ToPointF**(): PointF

**Returns** PointF


---

#### ToString

**ToString**(): string

Converts this PointM to a human readable string.

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Empty** | [PointM](PointM.md) | Represents a null PointM. |
| **IsEmpty** | bool |  |
