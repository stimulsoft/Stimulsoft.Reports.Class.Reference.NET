---
title: "StiUndefinedType Class"
---

## StiUndefinedType Class

**Namespace:** `Stimulsoft.Base`

Class describes a special class wrapper for the undefined type.

### Inheritance

Inherits from: TypeDelegator  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiUndefinedType**(string type) | Creates a new instance of the StiUndefinedType class. |

**StiUndefinedType**(**type**: string)

Creates a new instance of the StiUndefinedType class.

**Parameters**

- **type** (string)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Type** | string | Gets or sets the string representation of the type. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetAttributeFlagsImpl** | TypeAttributes |  |
| **GetInterfaces** | Type[] |  |
| **GetProperties** | PropertyInfo[] |  |
| **IsArrayImpl** | bool |  |
| **IsValueTypeImpl** | bool |  |
| **ToString** | string |  |

---

### Method Details

#### GetAttributeFlagsImpl

**GetAttributeFlagsImpl**(): TypeAttributes

**Returns** TypeAttributes


---

#### GetInterfaces

**GetInterfaces**(): Type[]

**Returns** Type[]


---

#### GetProperties

**GetProperties**(**bindingAttr**: BindingFlags): PropertyInfo[]

**Parameters**

- **bindingAttr** (BindingFlags)  

**Returns** PropertyInfo[]


---

#### IsArrayImpl

**IsArrayImpl**(): bool

**Returns** bool


---

#### IsValueTypeImpl

**IsValueTypeImpl**(): bool

**Returns** bool


---

#### ToString

**ToString**(): string

**Returns** string

