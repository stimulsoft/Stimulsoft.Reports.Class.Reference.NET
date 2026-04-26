---
title: "StiAppsColumn Class"
---

## StiAppsColumn Class

**Namespace:** `Stimulsoft.Base.AppsDatabase`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAppsColumn**() |  |
| **StiAppsColumn**(string name, [StiAppsColumnType](StiAppsColumnType.md) type) |  |
| **StiAppsColumn**(string name, [StiAppsColumnType](StiAppsColumnType.md) type, bool isNull) |  |

**StiAppsColumn**()

---

**StiAppsColumn**(**name**: string, **type**: [StiAppsColumnType](StiAppsColumnType.md))

**Parameters**

- **name** (string)  
- **type** ([StiAppsColumnType](StiAppsColumnType.md))  

---

**StiAppsColumn**(**name**: string, **type**: [StiAppsColumnType](StiAppsColumnType.md), **isNull**: bool)

**Parameters**

- **name** (string)  
- **type** ([StiAppsColumnType](StiAppsColumnType.md))  
- **isNull** (bool)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DefaultValue** | object |  |
| **Description** | string |  |
| **IsNull** | bool |  |
| **IsSystem** | bool |  |
| **Name** | string | Gets or sets a name of the table column. |
| **Size** | int? |  |
| **Type** | [StiAppsColumnType](StiAppsColumnType.md) | Get or sets a type of the table column. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConvertTypeToDataColumnType** | Type |  |
| **ToString** | string |  |

---

### Method Details

#### ConvertTypeToDataColumnType

**ConvertTypeToDataColumnType**(): Type

**Returns** Type


---

#### ToString

**ToString**(): string

**Returns** string

