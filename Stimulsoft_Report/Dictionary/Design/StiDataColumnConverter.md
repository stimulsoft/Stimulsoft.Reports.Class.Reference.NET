---
title: "StiDataColumnConverter Class"
---

## StiDataColumnConverter Class

**Namespace:** `Stimulsoft.Report.Dictionary.Design`

Converts StiDataColumn from one data type to another.

### Inheritance

Inherits from: TypeConverter  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanConvertFrom** | bool |  |
| **CanConvertTo** | bool |  |
| **ConvertFrom** | object |  |
| **ConvertTypeToString** `static` | string |  |
| **GetPropertiesSupported** | bool |  |

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

#### ConvertTypeToString `static`

**ConvertTypeToString**(**type**: Type): string

**Parameters**

- **type** (Type)  

**Returns** string


---

#### GetPropertiesSupported

**GetPropertiesSupported**(**context**: ITypeDescriptorContext): bool

**Parameters**

- **context** (ITypeDescriptorContext)  

**Returns** bool

