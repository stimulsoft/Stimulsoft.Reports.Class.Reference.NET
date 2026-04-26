---
title: "StiExpressionEnumConverter Class"
---

## StiExpressionEnumConverter Class

**Namespace:** `Stimulsoft.Base.Localization`

Provides a type converter to convert Enum objects to and from various other representations.

### Inheritance

Inherits from: [StiEnumConverter](StiEnumConverter.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiExpressionEnumConverter**() |  |
| **StiExpressionEnumConverter**(Type type) |  |

**StiExpressionEnumConverter**()

---

**StiExpressionEnumConverter**(**type**: Type)

**Parameters**

- **type** (Type)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConvertFrom** | object |  |
| **ConvertTo** | object |  |
| **GetStandardValuesExclusive** | bool |  |

---

### Method Details

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

#### GetStandardValuesExclusive

**GetStandardValuesExclusive**(**context**: ITypeDescriptorContext): bool

**Parameters**

- **context** (ITypeDescriptorContext)  

**Returns** bool

