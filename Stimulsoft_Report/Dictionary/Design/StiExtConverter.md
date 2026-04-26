---
title: "StiExtConverter Class"
---

## StiExtConverter Class

**Namespace:** `Stimulsoft.Report.Dictionary.Design`

Converts StiFile from one data type to another.

### Inheritance

Inherits from: TypeConverter  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanConvertFrom** | bool |  |
| **CanConvertTo** | bool |  |
| **CreateNewInstanceDescriptor** | object |  |
| **DecodeBytes** | byte[] |  |
| **Encode** *(+1 overloads)* | string |  |
| **EncodeBool** | string |  |
| **EncodeBytes** | string |  |
| **EncodeEnum** | string |  |
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

#### CreateNewInstanceDescriptor

**CreateNewInstanceDescriptor**(**info**: ConstructorInfo, ****: objectobjs): object

**Parameters**

- **info** (ConstructorInfo)  
- **** (objectobjs)  

**Returns** object


---

#### DecodeBytes

**DecodeBytes**(**value**: string): byte[]

**Parameters**

- **value** (string)  

**Returns** byte[]


---

#### Encode

**Encode**(****: stringargs): string

**Parameters**

- **** (stringargs)  

**Returns** string

---

**Encode**(**key**: string, **value**: string): string

**Parameters**

- **key** (string)  
- **value** (string)  

**Returns** string


---

#### EncodeBool

**EncodeBool**(**key**: string, **value**: bool, **defaultValue**: bool): string

**Parameters**

- **key** (string)  
- **value** (bool)  
- **defaultValue** (bool)  

**Returns** string


---

#### EncodeBytes

**EncodeBytes**(**key**: string, ****: bytevalue): string

**Parameters**

- **key** (string)  
- **** (bytevalue)  

**Returns** string


---

#### EncodeEnum

**EncodeEnum**(**key**: string, **value**: Enum, **defaultValue**: Enum): string

**Parameters**

- **key** (string)  
- **value** (Enum)  
- **defaultValue** (Enum)  

**Returns** string


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

