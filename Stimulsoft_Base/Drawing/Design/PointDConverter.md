---
title: "PointDConverter Class"
---

## PointDConverter Class

**Namespace:** `Stimulsoft.Base.Drawing.Design`

Converts a PointD object from one data type to another.

### Inheritance

Inherits from: TypeConverter  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanConvertFrom** | bool |  |
| **ConvertFrom** | object |  |
| **ConvertTo** | object |  |
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

#### ConvertFrom

**ConvertFrom**(**context**: ITypeDescriptorContext, **culture**: CultureInfo, **value**: object): object

**Parameters**

- **context** (ITypeDescriptorContext)  
- **culture** (CultureInfo)  
- **value** (object)  

**Returns** object


---

#### ConvertTo

**ConvertTo**(**context**: ITypeDescriptorContext, **culture**: CultureInfo, **value**: object, **destinationType**: Type): object

**Parameters**

- **context** (ITypeDescriptorContext)  
- **culture** (CultureInfo)  
- **value** (object)  
- **destinationType** (Type)  

**Returns** object


---

#### GetPropertiesSupported

**GetPropertiesSupported**(**context**: ITypeDescriptorContext): bool

**Parameters**

- **context** (ITypeDescriptorContext)  

**Returns** bool

