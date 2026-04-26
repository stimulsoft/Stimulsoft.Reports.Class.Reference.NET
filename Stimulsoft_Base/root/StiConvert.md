---
title: "StiConvert Class"
---

## StiConvert Class

**Namespace:** `Stimulsoft.Base`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DefaultDateOnlyForNullValues** `static` | [DateOnly](../System/DateOnly.md) |  |
| **DefaultDateTimeForNullValues** `static` | DateTime |  |
| **DefaultDateTimeOffsetForNullValues** `static` | DateTimeOffset |  |
| **UseDefaultDateOnlyForNullValues** `static` | bool |  |
| **UseDefaultDateTimeForNullValues** `static` | bool |  |
| **UseDefaultDateTimeOffsetForNullValues** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ChangeType** `static` *(+1 overloads)* | object | Changes a type of the specified value. |

---

### Method Details

#### ChangeType `static`

**ChangeType**(**value**: object, **conversionType**: Type): object

Changes a type of the specified value.

**Parameters**

- **value** (object) — A parameter which type will be changed.  
- **conversionType** (Type) — A type to which the value parameter will be converted.  

**Returns** object — Returns a value of the converted type.

---

**ChangeType**(**value**: object, **conversionType**: Type, **convertNulls**: bool): object

Changes a type of the specified value.

**Parameters**

- **value** (object) — A parameter which type will be changed.  
- **conversionType** (Type) — A type to which the value parameter will be converted.  
- **convertNulls** (bool) — A parameter which, when converting zero values, instead of null, returns String.Empty, false for Boolean, ' ' for char or null for DateTime.  

**Returns** object — Returns a value of the converted type.

