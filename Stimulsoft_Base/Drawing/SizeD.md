---
title: "SizeD Struct"
---

## SizeD Struct

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Implements: [IStiDefault](../Design/IStiDefault.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **SizeD**(double width, double height) | Initializes a new instance of the SizeD class from the specified dimensions. |

**SizeD**(**width**: double, **height**: double)

Initializes a new instance of the SizeD class from the specified dimensions.

**Parameters**

- **width** (double) — The width component of the new SizeD.  
- **height** (double) — The height component of the new SizeD.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Height** | double |  |
| **Width** | double |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateFromSize** `static` | [SizeD](SizeD.md) | Creates a new SizeD object based on the specified SizeF object. |
| **Equals** | bool | Tests to see whether the specified object is a SizeD with the same dimensions as this SizeD. |
| **GetHashCode** | int | Returns a hash code for this SizeD structure. |
| **Multiply** | [SizeD](SizeD.md) | Multiplies the size on number. |
| **ToSize** | Size | Converts the specified SizeD to a Size. |
| **ToSizeF** | SizeF |  |
| **ToString** | string |  |

---

### Method Details

#### CreateFromSize `static`

**CreateFromSize**(**size**: SizeF): [SizeD](SizeD.md)

Creates a new SizeD object based on the specified SizeF object.

**Parameters**

- **size** (SizeF)  

**Returns** [SizeD](SizeD.md)


---

#### Equals

**Equals**(**obj**: object): bool

Tests to see whether the specified object is a SizeD with the same dimensions as this SizeD.

**Parameters**

- **obj** (object) — The Object to test.  

**Returns** bool — This method returns true if obj is a SizeD and has the same width and height as this SizeD; otherwise, false.


---

#### GetHashCode

**GetHashCode**(): int

Returns a hash code for this SizeD structure.

**Returns** int — An integer value that specifies a hash value for this SizeD structure.


---

#### Multiply

**Multiply**(**multipleFactor**: double): [SizeD](SizeD.md)

Multiplies the size on number.

**Parameters**

- **multipleFactor** (double) — Number.  

**Returns** [SizeD](SizeD.md) — Multiplied size.


---

#### ToSize

**ToSize**(): Size

Converts the specified SizeD to a Size.

**Returns** Size


---

#### ToSizeF

**ToSizeF**(): SizeF

**Returns** SizeF


---

#### ToString

**ToString**(): string

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Empty** | [SizeD](SizeD.md) | Initializes a new instance of the SizeD class. |
| **IsDefault** | bool |  |
| **IsEmpty** | bool |  |
