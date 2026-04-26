---
title: "FontConverter Class"
---

## FontConverter Class

**Namespace:** `Stimulsoft.Drawing`

### Inheritance

Inherits from: TypeConverter  

### Constructors

| Constructor | Description |
| --- | --- |
| **FontConverter**() |  |

**FontConverter**()


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanConvertFrom** | bool |  |
| **CanConvertTo** | bool |  |
| **ConvertFrom** | object |  |
| **CreateInstance** | object |  |
| **GetCreateInstanceSupported** | bool |  |
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

#### CreateInstance

**CreateInstance**(**context**: ITypeDescriptorContext, **propertyValues**: IDictionary): object

**Parameters**

- **context** (ITypeDescriptorContext)  
- **propertyValues** (IDictionary)  

**Returns** object


---

#### GetCreateInstanceSupported

**GetCreateInstanceSupported**(**context**: ITypeDescriptorContext): bool

**Parameters**

- **context** (ITypeDescriptorContext)  

**Returns** bool


---

#### GetPropertiesSupported

**GetPropertiesSupported**(**context**: ITypeDescriptorContext): bool

**Parameters**

- **context** (ITypeDescriptorContext)  

**Returns** bool

