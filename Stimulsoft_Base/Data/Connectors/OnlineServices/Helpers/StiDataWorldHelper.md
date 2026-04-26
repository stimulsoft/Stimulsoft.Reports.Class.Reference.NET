---
title: "StiDataWorldHelper Class"
---

## StiDataWorldHelper Class

**Namespace:** `Stimulsoft.Base.Data.Connectors.OnlineServices.Helpers`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataWorldHelper**(string connectionString) |  |

**StiDataWorldHelper**(**connectionString**: string)

**Parameters**

- **connectionString** (string)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ConnectionString** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetColumns** | List<[StiDataColumnSchema](../../../../root/StiDataColumnSchema.md)> |  |
| **GetDataTable** | DataTable |  |
| **GetTableNames** | List<string> |  |
| **RetrieveSchema** | [StiDataSchema](../../../../root/StiDataSchema.md) |  |

---

### Method Details

#### GetColumns

**GetColumns**(**collectionName**: string): List<[StiDataColumnSchema](../../../../root/StiDataColumnSchema.md)>

**Parameters**

- **collectionName** (string)  

**Returns** List<[StiDataColumnSchema](../../../../root/StiDataColumnSchema.md)>


---

#### GetDataTable

**GetDataTable**(**collectionName**: string, **query**: string): DataTable

**Parameters**

- **collectionName** (string)  
- **query** (string)  

**Returns** DataTable


---

#### GetTableNames

**GetTableNames**(): List<string>

**Returns** List<string>


---

#### RetrieveSchema

**RetrieveSchema**(**allowException**: bool): [StiDataSchema](../../../../root/StiDataSchema.md)

**Parameters**

- **allowException** (bool)  

**Returns** [StiDataSchema](../../../../root/StiDataSchema.md)


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Database** | string |  |
| **Owner** | string |  |
| **Token** | string |  |
