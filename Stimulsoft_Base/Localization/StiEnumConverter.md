---
title: "StiEnumConverter Class"
---

## StiEnumConverter Class

**Namespace:** `Stimulsoft.Base.Localization`

Provides a type converter to convert Enum objects to and from various other representations.

### Inheritance

Inherits from: TypeConverter  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiEnumConverter**() |  |
| **StiEnumConverter**(Type type) |  |

**StiEnumConverter**()

---

**StiEnumConverter**(**type**: Type)

**Parameters**

- **type** (Type)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Type** | Type |  |
| **Values** | StandardValuesCollection |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanConvertFrom** | bool |  |
| **CanConvertTo** | bool |  |
| **ConvertFrom** | object |  |
| **GetLocName** | string |  |
| **GetStandardValues** | StandardValuesCollection |  |
| **GetStandardValuesExclusive** | bool |  |
| **GetStandardValuesSupported** | bool |  |
| **IsValid** | bool |  |

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

#### GetLocName

**GetLocName**(**typeName**: string, **valueName**: string): string

**Parameters**

- **typeName** (string)  
- **valueName** (string)  

**Returns** string


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


---

#### IsValid

**IsValid**(**context**: ITypeDescriptorContext, **value**: object): bool

**Parameters**

- **context** (ITypeDescriptorContext)  
- **value** (object)  

**Returns** bool


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **EnumType** | Type |  |
