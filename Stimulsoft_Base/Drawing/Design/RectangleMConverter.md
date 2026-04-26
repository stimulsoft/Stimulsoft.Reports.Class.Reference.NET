---
title: "RectangleMConverter Class"
---

## RectangleMConverter Class

**Namespace:** `Stimulsoft.Base.Drawing.Design`

Converts rectangles from one data type to another.

### Inheritance

Inherits from: TypeConverter  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanConvertFrom** | bool |  |
| **ConvertFrom** | object |  |
| **ConvertTo** | object |  |
| **GetProperties** | PropertyDescriptorCollection |  |
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

#### GetProperties

**GetProperties**(**context**: ITypeDescriptorContext, **value**: object, ****: Attributeattributes): PropertyDescriptorCollection

**Parameters**

- **context** (ITypeDescriptorContext)  
- **value** (object)  
- **** (Attributeattributes)  

**Returns** PropertyDescriptorCollection


---

#### GetPropertiesSupported

**GetPropertiesSupported**(**context**: ITypeDescriptorContext): bool

**Parameters**

- **context** (ITypeDescriptorContext)  

**Returns** bool

