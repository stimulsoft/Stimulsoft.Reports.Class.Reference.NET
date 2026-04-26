---
title: "StiMargin Class"
---

## StiMargin Class

**Namespace:** `Stimulsoft.Report.Dashboard`

### Inheritance

Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMargin**() | Creates a new object of the type StiMargin. |
| **StiMargin**(double all) | Creates a new object of the type StiMargin. |
| **StiMargin**(double left, double top, double right, double bottom) | Creates a new object of the type StiMargin. |

**StiMargin**()

Creates a new object of the type StiMargin.

---

**StiMargin**(**all**: double)

Creates a new object of the type StiMargin.

**Parameters**

- **all** (double) — The margin size for all sides of the object.  

---

**StiMargin**(**left**: double, **top**: double, **right**: double, **bottom**: double)

Creates a new object of the type StiMargin.

**Parameters**

- **left** (double) — Left margin size on the object.  
- **top** (double) — Top margin size on the object.  
- **right** (double) — Right margin size on the object.  
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
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **Equals** | bool | Tests to see whether the specified object is a StiMargin with the same dimensions as this StiMargin. |
| **GetHashCode** | int | Returns a hash code for this StiMargins structure. |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Clone

**Clone**(): object

Creates a new object that is a copy of the current instance.

**Returns** object — A new object that is a copy of this instance.


---

#### Equals

**Equals**(**obj**: object): bool

Tests to see whether the specified object is a StiMargin with the same dimensions as this StiMargin.

**Parameters**

- **obj** (object) — The Object to test.  

**Returns** bool — This method returns true if obj is a StiMargin and has the same width and height as this StiMargin; otherwise, false.


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

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md), **defLeft**: double, **defTop**: double, **defRight**: double, **defBotttom**: double): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  
- **defLeft** (double)  
- **defTop** (double)  
- **defRight** (double)  
- **defBotttom** (double)  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Empty** | [StiMargin](StiMargin.md) |  |
| **IsEmpty** | bool |  |
