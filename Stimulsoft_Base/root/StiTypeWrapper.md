---
title: "StiTypeWrapper Class"
---

## StiTypeWrapper Class

**Namespace:** `Stimulsoft.Base`

Class describes a wrapper for the type.

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTypeWrapper**(Type type) | Creates a new instance of the StiTypeWrapper class. |

**StiTypeWrapper**(**type**: Type)

Creates a new instance of the StiTypeWrapper class.

**Parameters**

- **type** (Type) — Type for which wrapper is described.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Type** | Type | Gets or sets the Type for which is described wrapper. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetBaseTypeWrappers** `static` | [StiTypeWrapper](StiTypeWrapper.md)[] | Gets the array of base simple types. |
| **GetTypeWrappers** `static` | [StiTypeWrapper](StiTypeWrapper.md)[] | Gets the array of simple types. |
| **IsAllowedType** `static` | bool | Returns true if specified type is a simple type for Stimulsoft Reports. |
| **ToString** *(+1 overloads)* | string |  |

---

### Method Details

#### GetBaseTypeWrappers `static`

**GetBaseTypeWrappers**(): [StiTypeWrapper](StiTypeWrapper.md)[]

Gets the array of base simple types.

**Returns** [StiTypeWrapper](StiTypeWrapper.md)[] — Array of base simple types.


---

#### GetTypeWrappers `static`

**GetTypeWrappers**(): [StiTypeWrapper](StiTypeWrapper.md)[]

Gets the array of simple types.

**Returns** [StiTypeWrapper](StiTypeWrapper.md)[] — Array of simple types.


---

#### IsAllowedType `static`

**IsAllowedType**(**type**: Type): bool

Returns true if specified type is a simple type for Stimulsoft Reports.

**Parameters**

- **type** (Type)  

**Returns** bool


---

#### ToString

**ToString**(): string

**Returns** string

---

**ToString**(**type**: Type): string

**Parameters**

- **type** (Type)  

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **SimpleTypes** | List<Type> |  |
