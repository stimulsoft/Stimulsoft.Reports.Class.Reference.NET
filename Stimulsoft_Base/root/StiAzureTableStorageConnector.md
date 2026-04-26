---
title: "StiAzureTableStorageConnector Class"
---

## StiAzureTableStorageConnector Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: StiDbNoSqlDataConnector  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAzureTableStorageConnector**(string connectionString) |  |

**StiAzureTableStorageConnector**(**connectionString**: string)

**Parameters**

- **connectionString** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConvertDateTimeToJsonStr** | string |  |
| **Get** `static` | [StiAzureTableStorageConnector](StiAzureTableStorageConnector.md) |  |
| **GetColumns** | List<[StiDataColumnSchema](StiDataColumnSchema.md)> |  |
| **GetDataTable** | DataTable |  |
| **GetSampleConnectionString** | string | Returns sample of the connection string to this connector. |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) | Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable). |
| **TestConnection** | [StiTestConnectionResult](StiTestConnectionResult.md) | Returns StiTestConnectionResult that is the information of whether the connection string specified in this class is correct. |

---

### Method Details

#### ConvertDateTimeToJsonStr

**ConvertDateTimeToJsonStr**(**date**: DateTime): string

**Parameters**

- **date** (DateTime)  

**Returns** string


---

#### Get `static`

**Get**(**connectionString**: string): [StiAzureTableStorageConnector](StiAzureTableStorageConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiAzureTableStorageConnector](StiAzureTableStorageConnector.md)


---

#### GetColumns

**GetColumns**(**collectionName**: string): List<[StiDataColumnSchema](StiDataColumnSchema.md)>

**Parameters**

- **collectionName** (string)  

**Returns** List<[StiDataColumnSchema](StiDataColumnSchema.md)>


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

**RetrieveSchema**(**allowException**: bool): [StiDataSchema](StiDataSchema.md)

Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable).

**Parameters**

- **allowException** (bool)  

**Returns** [StiDataSchema](StiDataSchema.md)


---

#### TestConnection

**TestConnection**(): [StiTestConnectionResult](StiTestConnectionResult.md)

Returns StiTestConnectionResult that is the information of whether the connection string specified in this class is correct.

**Returns** [StiTestConnectionResult](StiTestConnectionResult.md) — The result of testing the connection string.

