---
title: "StiActivator Class"
---

## StiActivator Class

**Namespace:** `Stimulsoft.Base`

Helps to create objects of the specified type.

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowTypeNotFoundException** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateObject** `static` *(+3 overloads)* | object | Creates the object of the specified type. |

---

### Method Details

#### CreateObject `static`

**CreateObject**(**type**: Type): object

Creates the object of the specified type.

**Parameters**

- **type** (Type) — The type of the created object.  

**Returns** object — The Created object.

---

**CreateObject**(**typeName**: string): object

Creates the object of the specified type.

**Parameters**

- **typeName** (string) — The type of the created object.  

**Returns** object — The Created object.

---

**CreateObject**(**type**: Type, ****: objectarguments): object

Creates the object of the specified type.

**Parameters**

- **type** (Type) — The type of the created object.  
- **** (objectarguments)  

**Returns** object — The Created object.

---

**CreateObject**(**typeName**: string, ****: objectarguments): object

Creates the object of the specified type.

**Parameters**

- **typeName** (string) — The type of the created object.  
- **** (objectarguments)  

**Returns** object — The Created object.

