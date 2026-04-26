---
title: "SizeM Struct"
---

## SizeM Struct

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Implements: [IStiDefault](../Design/IStiDefault.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **SizeM**(decimal width, decimal height) | Initializes a new instance of the SizeM class from the specified dimensions. |

**SizeM**(**width**: decimal, **height**: decimal)

Initializes a new instance of the SizeM class from the specified dimensions.

**Parameters**

- **width** (decimal) — The width component of the new SizeM.  
- **height** (decimal) — The height component of the new SizeM.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Height** | decimal |  |
| **Width** | decimal |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Equals** | bool | Tests to see whether the specified object is a SizeM with the same dimensions as this SizeM. |
| **GetHashCode** | int | Returns a hash code for this SizeM structure. |
| **ToSizeD** | [SizeD](SizeD.md) |  |
| **ToSizeF** | SizeF |  |
| **ToString** | string |  |

---

### Method Details

#### Equals

**Equals**(**obj**: object): bool

Tests to see whether the specified object is a SizeM with the same dimensions as this SizeM.

**Parameters**

- **obj** (object) — The Object to test.  

**Returns** bool — This method returns true if obj is a SizeM and has the same width and height as this SizeM; otherwise, false.


---

#### GetHashCode

**GetHashCode**(): int

Returns a hash code for this SizeM structure.

**Returns** int — An integer value that specifies a hash value for this SizeM structure.


---

#### ToSizeD

**ToSizeD**(): [SizeD](SizeD.md)

**Returns** [SizeD](SizeD.md)


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
| **Empty** | [SizeM](SizeM.md) | Initializes a new instance of the SizeM class. |
| **IsDefault** | bool |  |
| **IsEmpty** | bool |  |
