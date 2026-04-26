---
title: "StiType Class"
---

## StiType Class

**Namespace:** `Stimulsoft.Report.Dictionary`

This class describes wrapper for type registered in dictionary data.

### Constructors

| Constructor | Description |
| --- | --- |
| **StiType**(string name, Type type) | Creates a new object of the type StiType. |

**StiType**(**name**: string, **type**: Type)

Creates a new object of the type StiType.

**Parameters**

- **name** (string) — Name of type.  
- **type** (Type) — Registereg type.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Name** | string | Gets or sets name of type. |
| **Type** | Type | Gets or sets the registered type. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetBaseTypes** `static` | [StiTypesCollection](StiTypesCollection.md) | Returns the collection of all base registered types in dictionary data. |
| **GetTypeFromTypeMode** `static` | Type |  |
| **GetTypeModeFromType** `static` | Type |  |
| **GetTypes** `static` | [StiTypesCollection](StiTypesCollection.md) | Returns the collection of all registered types in dictionary data. |
| **IsDateTimeType** `static` | bool |  |
| **IsFloatType** `static` | bool |  |
| **IsIntegerType** `static` | bool |  |
| **ToString** | string |  |

---

### Method Details

#### GetBaseTypes `static`

**GetBaseTypes**(): [StiTypesCollection](StiTypesCollection.md)

Returns the collection of all base registered types in dictionary data.

**Returns** [StiTypesCollection](StiTypesCollection.md) — Collection of types.


---

#### GetTypeFromTypeMode `static`

**GetTypeFromTypeMode**(**type**: Type, **typeMode**: [StiTypeMode](StiTypeMode.md)): Type

**Parameters**

- **type** (Type)  
- **typeMode** ([StiTypeMode](StiTypeMode.md))  

**Returns** Type


---

#### GetTypeModeFromType `static`

**GetTypeModeFromType**(**type**: Type, **typeMode**: [StiTypeMode](StiTypeMode.md)): Type

**Parameters**

- **type** (Type)  
- **typeMode** ([StiTypeMode](StiTypeMode.md))  

**Returns** Type


---

#### GetTypes `static`

**GetTypes**(): [StiTypesCollection](StiTypesCollection.md)

Returns the collection of all registered types in dictionary data.

**Returns** [StiTypesCollection](StiTypesCollection.md) — Collection of types.


---

#### IsDateTimeType `static`

**IsDateTimeType**(**type**: Type): bool

**Parameters**

- **type** (Type)  

**Returns** bool


---

#### IsFloatType `static`

**IsFloatType**(**type**: Type): bool

**Parameters**

- **type** (Type)  

**Returns** bool


---

#### IsIntegerType `static`

**IsIntegerType**(**type**: Type): bool

**Parameters**

- **type** (Type)  

**Returns** bool


---

#### ToString

**ToString**(): string

**Returns** string

