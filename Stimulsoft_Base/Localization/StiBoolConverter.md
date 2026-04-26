---
title: "StiBoolConverter Class"
---

## StiBoolConverter Class

**Namespace:** `Stimulsoft.Base.Localization`

Provides a type converter to convert Boolean objects to and from various other representations.

### Inheritance

Inherits from: TypeConverter  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanConvertFrom** | bool |  |
| **CanConvertTo** | bool |  |
| **ConvertFrom** | object |  |
| **ConvertTo** | object |  |
| **GetStandardValues** | StandardValuesCollection |  |
| **GetStandardValuesExclusive** | bool |  |
| **GetStandardValuesSupported** | bool |  |

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

#### ConvertTo

**ConvertTo**(**context**: ITypeDescriptorContext, **culture**: CultureInfo, **value**: object, **destinationType**: Type): object

**Parameters**

- **context** (ITypeDescriptorContext)  
- **culture** (CultureInfo)  
- **value** (object)  
- **destinationType** (Type)  

**Returns** object


---

#### GetStandardValues

**GetStandardValues**(**context**: ITypeDescriptorContext): StandardValuesCollection

**Parameters**

- **context** (ITypeDescriptorContext)  

**Returns** StandardValuesCollection


---

#### GetStandardValuesExclusive

**GetStandardValuesExclusive**(**context**: ITypeDescriptorContext): bool

**Parameters**

- **context** (ITypeDescriptorContext)  

**Returns** bool


---

#### GetStandardValuesSupported

**GetStandardValuesSupported**(**context**: ITypeDescriptorContext): bool

**Parameters**

- **context** (ITypeDescriptorContext)  

**Returns** bool

