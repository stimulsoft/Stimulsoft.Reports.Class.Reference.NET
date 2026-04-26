---
title: "StiNoSqlDataConnector Class"
---

## StiNoSqlDataConnector Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: [StiDataConnector](StiDataConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiNoSqlDataConnector**(string connectionString) |  |

**StiNoSqlDataConnector**(**connectionString**: string)

**Parameters**

- **connectionString** (string)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ConnectionString** | string | Gets connection string to the database. |
| **FolderAssembly** | string |  |
| **NameAssembly** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Get** `static` | [StiNoSqlDataConnector](StiNoSqlDataConnector.md) |  |
| **GetColumns** | List<[StiDataColumnSchema](StiDataColumnSchema.md)> |  |
| **GetDataTable** | DataTable |  |
| **GetSampleConnectionString** | string | Returns sample of the connection string to this connector. |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) | Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable). |
| **TestConnection** | [StiTestConnectionResult](StiTestConnectionResult.md) | Returns StiTestConnectionResult that is the information of whether the connection string specified in this class is correct. |

---

### Method Details

#### Get `static`

**Get**(**ident**: [StiConnectionIdent](StiConnectionIdent.md), **connectionString**: string): [StiNoSqlDataConnector](StiNoSqlDataConnector.md)

**Parameters**

- **ident** ([StiConnectionIdent](StiConnectionIdent.md))  
- **connectionString** (string)  

**Returns** [StiNoSqlDataConnector](StiNoSqlDataConnector.md)


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

