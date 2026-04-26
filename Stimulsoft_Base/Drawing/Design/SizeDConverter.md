---
title: "SizeDConverter Class"
---

## SizeDConverter Class

**Namespace:** `Stimulsoft.Base.Drawing.Design`

The SizeConverter class is used to convert from one data type to another.

### Inheritance

Inherits from: TypeConverter  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanConvertFrom** | bool |  |
| **CanConvertTo** | bool |  |
| **ConvertFrom** | object |  |
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

