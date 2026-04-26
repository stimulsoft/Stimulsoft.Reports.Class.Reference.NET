---
title: "StiFirebaseConnector Class"
---

## StiFirebaseConnector Class

**Namespace:** `Stimulsoft.Base.Data.Connectors.Google`

### Inheritance

Inherits from: StiDbNoSqlDataConnector  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiFirebaseConnector**(string connectionString) |  |

**StiFirebaseConnector**(**connectionString**: string)

**Parameters**

- **connectionString** (string)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AuthSecret** | string |  |
| **BasePath** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Get** `static` | [StiFirebaseConnector](StiFirebaseConnector.md) |  |
| **GetColumns** | List<[StiDataColumnSchema](../../../root/StiDataColumnSchema.md)> |  |
| **GetDataSet** | DataSet |  |
| **GetDataTable** | DataTable |  |
| **GetSampleConnectionString** | string | Returns sample of the connection string to this connector. |
| **RetrieveSchema** | [StiDataSchema](../../../root/StiDataSchema.md) |  |
| **TestConnection** | [StiTestConnectionResult](../../../root/StiTestConnectionResult.md) |  |

---

### Method Details

#### Get `static`

**Get**(**connectionString**: string): [StiFirebaseConnector](StiFirebaseConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiFirebaseConnector](StiFirebaseConnector.md)


---

#### GetColumns

**GetColumns**(**collectionName**: string): List<[StiDataColumnSchema](../../../root/StiDataColumnSchema.md)>

**Parameters**

- **collectionName** (string)  

**Returns** List<[StiDataColumnSchema](../../../root/StiDataColumnSchema.md)>


---

#### GetDataSet

**GetDataSet**(): DataSet

**Returns** DataSet


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

Returns sample of the connection string to this connector.

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

