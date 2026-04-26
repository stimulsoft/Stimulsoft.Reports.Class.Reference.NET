---
title: "StiCultureConverter Class"
---

## StiCultureConverter Class

**Namespace:** `Stimulsoft.Report.Design`

### Inheritance

Inherits from: TypeConverter  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanConvertTo** | bool |  |
| **ConvertTo** | object |  |
| **GetProperties** | PropertyDescriptorCollection |  |
| **GetPropertiesSupported** | bool |  |

---

### Method Details

#### CanConvertTo

**CanConvertTo**(**context**: ITypeDescriptorContext, **destinationType**: Type): bool

**Parameters**

- **context** (ITypeDescriptorContext)  
- **destinationType** (Type)  

**Returns** bool


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

