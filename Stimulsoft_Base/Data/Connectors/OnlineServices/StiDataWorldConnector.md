---
title: "StiDataWorldConnector Class"
---

## StiDataWorldConnector Class

**Namespace:** `Stimulsoft.Base.Data.Connectors.OnlineServices`

### Inheritance

Inherits from: StiDbNoSqlDataConnector  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataWorldConnector**(string connectionString) |  |

**StiDataWorldConnector**(**connectionString**: string)

**Parameters**

- **connectionString** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Get** `static` | [StiDataWorldConnector](StiDataWorldConnector.md) |  |
| **GetColumns** | List<[StiDataColumnSchema](../../../root/StiDataColumnSchema.md)> |  |
| **GetDataTable** | DataTable |  |
| **GetSampleConnectionString** | string |  |
| **RetrieveSchema** | [StiDataSchema](../../../root/StiDataSchema.md) |  |
| **TestConnection** | [StiTestConnectionResult](../../../root/StiTestConnectionResult.md) |  |

---

### Method Details

#### Get `static`

**Get**(**connectionString**: string): [StiDataWorldConnector](StiDataWorldConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiDataWorldConnector](StiDataWorldConnector.md)


---

#### GetColumns

**GetColumns**(**collectionName**: string): List<[StiDataColumnSchema](../../../root/StiDataColumnSchema.md)>

**Parameters**

- **collectionName** (string)  

**Returns** List<[StiDataColumnSchema](../../../root/StiDataColumnSchema.md)>


---

#### GetDataTable

**GetDataTable**(**collectionName**: string, **query**: string, **index**: int?, **count**: int?): DataTable

**Parameters**

- **collectionName** (string)  
- **query** (string)  
- **index** (int?)  
- **count** (int?)  

**Returns** DataTable


---

#### GetSampleConnectionString

**GetSampleConnectionString**(): string

**Returns** string


---

#### RetrieveSchema

**RetrieveSchema**(**allowException**: bool): [StiDataSchema](../../../root/StiDataSchema.md)

**Parameters**

- **allowException** (bool)  

**Returns** [StiDataSchema](../../../root/StiDataSchema.md)


---

#### TestConnection

**TestConnection**(): [StiTestConnectionResult](../../../root/StiTestConnectionResult.md)

**Returns** [StiTestConnectionResult](../../../root/StiTestConnectionResult.md)

