---
title: "StiDialogInfoConverter Class"
---

## StiDialogInfoConverter Class

**Namespace:** `Stimulsoft.Report.Dictionary.Design`

Converts StiDialogInfo from one data type to another.

### Inheritance

Inherits from: TypeConverter  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanConvertFrom** | bool |  |
| **CanConvertTo** | bool |  |
| **ConvertDialogInfoToString** `static` | string |  |
| **ConvertFrom** | object |  |
| **ConvertFromStringToDialogInfo** `static` | [StiDialogInfo](../StiDialogInfo.md) |  |
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

#### ConvertDialogInfoToString `static`

**ConvertDialogInfoToString**(**info**: [StiDialogInfo](../StiDialogInfo.md)): string

**Parameters**

- **info** ([StiDialogInfo](../StiDialogInfo.md))  

**Returns** string


---

#### ConvertFrom

**ConvertFrom**(**context**: ITypeDescriptorContext, **culture**: CultureInfo, **value**: object): object

**Parameters**

- **context** (ITypeDescriptorContext)  
- **culture** (CultureInfo)  
- **value** (object)  

**Returns** object


---

#### ConvertFromStringToDialogInfo `static`

**ConvertFromStringToDialogInfo**(**str**: string): [StiDialogInfo](../StiDialogInfo.md)

**Parameters**

- **str** (string)  

**Returns** [StiDialogInfo](../StiDialogInfo.md)


---

#### GetPropertiesSupported

**GetPropertiesSupported**(**context**: ITypeDescriptorContext): bool

**Parameters**

- **context** (ITypeDescriptorContext)  

**Returns** bool

