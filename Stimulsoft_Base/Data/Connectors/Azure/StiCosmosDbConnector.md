---
title: "StiCosmosDbConnector Class"
---

## StiCosmosDbConnector Class

**Namespace:** `Stimulsoft.Base.Data.Connectors.Azure`

### Inheritance

Inherits from: StiDbNoSqlDataConnector  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCosmosDbConnector**(string connectionString, [StiCosmosDbApi](../../../root/StiCosmosDbApi.md) api) |  |

**StiCosmosDbConnector**(**connectionString**: string, **api**: [StiCosmosDbApi](../../../root/StiCosmosDbApi.md))

**Parameters**

- **connectionString** (string)  
- **api** ([StiCosmosDbApi](../../../root/StiCosmosDbApi.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Api** | [StiCosmosDbApi](../../../root/StiCosmosDbApi.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConvertDateTimeToJsonStr** | string |  |
| **Get** `static` | [StiCosmosDbConnector](StiCosmosDbConnector.md) |  |
| **GetColumns** | List<[StiDataColumnSchema](../../../root/StiDataColumnSchema.md)> |  |
| **GetDataTable** | DataTable |  |
| **GetSampleConnectionString** | string |  |
| **RetrieveSchema** | [StiDataSchema](../../../root/StiDataSchema.md) |  |
| **TestConnection** | [StiTestConnectionResult](../../../root/StiTestConnectionResult.md) |  |

---

### Method Details

#### ConvertDateTimeToJsonStr

**ConvertDateTimeToJsonStr**(**date**: DateTime): string

**Parameters**

- **date** (DateTime)  

**Returns** string


---

#### Get `static`

**Get**(**connectionString**: string): [StiCosmosDbConnector](StiCosmosDbConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiCosmosDbConnector](StiCosmosDbConnector.md)


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

