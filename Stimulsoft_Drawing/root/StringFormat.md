---
title: "StringFormat Class"
---

## StringFormat Class

**Namespace:** `Stimulsoft.Drawing`

### Inheritance

Implements: IDisposable, ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StringFormat**() |  |
| **StringFormat**([StringFormat](StringFormat.md) format) |  |

**StringFormat**()

---

**StringFormat**(**format**: [StringFormat](StringFormat.md))

**Parameters**

- **format** ([StringFormat](StringFormat.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **GenericDefault** `static` | [StringFormat](StringFormat.md) |  |
| **GenericTypographic** `static` | [StringFormat](StringFormat.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **Dispose** | void |  |
| **GetTabStops** | float[] |  |
| **SetMeasurableCharacterRanges** | void |  |
| **SetTabStops** | void |  |
| **ToString** | string |  |

---

### Method Details

#### Clone

**Clone**(): object

**Returns** object


---

#### Dispose

**Dispose**(): void


---

#### GetTabStops

**GetTabStops**(**firstTabOffset**: float): float[]

**Parameters**

- **firstTabOffset** (float)  

**Returns** float[]


---

#### SetMeasurableCharacterRanges

**SetMeasurableCharacterRanges**(****: CharacterRangeranges): void

**Parameters**

- **** (CharacterRangeranges)  


---

#### SetTabStops

**SetTabStops**(**firstTabOffset**: float, ****: floattabStops): void

**Parameters**

- **firstTabOffset** (float)  
- **** (floattabStops)  


---

#### ToString

**ToString**(): string

**Returns** string

