---
title: "StiBigQuerySource Class"
---

## StiBigQuerySource Class

**Namespace:** `Stimulsoft.Report.Dictionary.DataSources.Google`

### Inheritance

Inherits from: [StiNoSqlSource](../../StiNoSqlSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiBigQuerySource**() | Creates a new object of the type StiBigQuerySource. |
| **StiBigQuerySource**(string nameInSource, string name) |  |
| **StiBigQuerySource**(string nameInSource, string name, string alias) |  |
| **StiBigQuerySource**(string nameInSource, string name, string alias, string sqlCommand) |  |

**StiBigQuerySource**()

Creates a new object of the type StiBigQuerySource.

---

**StiBigQuerySource**(**nameInSource**: string, **name**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  

---

**StiBigQuerySource**(**nameInSource**: string, **name**: string, **alias**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  

---

**StiBigQuerySource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  
- **sqlCommand** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddParameter** | StiDataParameter |  |
| **ConvertDbTypeToTypeInternal** | Type |  |
| **GetDataAdapterType** | Type |  |
| **GetParameterTypesEnum** | Type |  |

---

### Method Details

#### AddParameter

**AddParameter**(): StiDataParameter

**Returns** StiDataParameter


---

#### ConvertDbTypeToTypeInternal

**ConvertDbTypeToTypeInternal**(**sqlType**: int): Type

**Parameters**

- **sqlType** (int)  

**Returns** Type


---

#### GetDataAdapterType

**GetDataAdapterType**(): Type

**Returns** Type


---

#### GetParameterTypesEnum

**GetParameterTypesEnum**(): Type

**Returns** Type

