---
title: "RangeConverter Class"
---

## RangeConverter Class

**Namespace:** `Stimulsoft.Report.Design`

Converts Range from one data type to another.

### Inheritance

Inherits from: TypeConverter  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanConvertFrom** | bool |  |
| **CanConvertTo** | bool |  |
| **ConvertFrom** | object |  |
| **GetPropertiesSupported** | bool |  |
| **RangeToString** `static` | string |  |
| **StringToRange** `static` | [Range](../root/Range.md) |  |

---

### Method Details

#### CanConvertFrom

**CanConvertFrom**(**context**: ITypeDescriptorContext, **sourceType**: Type): bool

**Parameters**

- **context** (ITypeDescriptorContext)  
- **sourceType** (Type)  

**Returns** bool


---

#### CanConvertTo

**CanConvertTo**(**context**: ITypeDescriptorContext, **destinationType**: Type): bool

**Parameters**

- **context** (ITypeDescriptorContext)  
- **destinationType** (Type)  

**Returns** bool


---

#### ConvertFrom

**ConvertFrom**(**context**: ITypeDescriptorContext, **culture**: CultureInfo, **value**: object): object

**Parameters**

- **context** (ITypeDescriptorContext)  
- **culture** (CultureInfo)  
- **value** (object)  

**Returns** object


---

#### GetPropertiesSupported

**GetPropertiesSupported**(**context**: ITypeDescriptorContext): bool

**Parameters**

- **context** (ITypeDescriptorContext)  

**Returns** bool


---

#### RangeToString `static`

**RangeToString**(**range**: [Range](../root/Range.md)): string

**Parameters**

- **range** ([Range](../root/Range.md))  

**Returns** string


---

#### StringToRange `static`

**StringToRange**(**str**: string): [Range](../root/Range.md)

**Parameters**

- **str** (string)  

**Returns** [Range](../root/Range.md)

