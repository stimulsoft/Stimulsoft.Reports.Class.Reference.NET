---
title: "StiMargins Class"
---

## StiMargins Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMargins**() | Creates a new object of the type StiMargins. |
| **StiMargins**(double all) | Creates a new object of the type StiMargins. |
| **StiMargins**(double left, double right, double top, double bottom) | Creates a new object of the type StiMargins. |

**StiMargins**()

Creates a new object of the type StiMargins.

---

**StiMargins**(**all**: double)

Creates a new object of the type StiMargins.

**Parameters**

- **all** (double) — The padding size for all sides of the object.  

---

**StiMargins**(**left**: double, **right**: double, **top**: double, **bottom**: double)

Creates a new object of the type StiMargins.

**Parameters**

- **left** (double) — Left margin size on the object.  
- **right** (double) — Right margin size on the object.  
- **top** (double) — Top margin size on the object.  
- **bottom** (double) — Bottom margin size on the object.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Bottom** | double |  |
| **Left** | double |  |
| **Right** | double |  |
| **Top** | double |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Apply** | [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) |  |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **Equals** | bool | Tests to see whether the specified object is a SizeD with the same dimensions as this SizeD. |
| **GetHashCode** | int | Returns a hash code for this StiMargins structure. |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Apply

**Apply**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  

**Returns** [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)


---

#### Clone

**Clone**(): object

Creates a new object that is a copy of the current instance.

**Returns** object — A new object that is a copy of this instance.


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

Returns a hash code for this StiMargins structure.

**Returns** int — An integer value that specifies a hash value for this StiMargins structure.


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**defLeft**: double, **defRight**: double, **defTop**: double, **defBotttom**: double): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **defLeft** (double)  
- **defRight** (double)  
- **defTop** (double)  
- **defBotttom** (double)  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Empty** | [StiMargins](StiMargins.md) |  |
| **IsEmpty** | bool |  |
