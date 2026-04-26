---
title: "StiGraphQLConnector Class"
---

## StiGraphQLConnector Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: StiDbNoSqlDataConnector  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGraphQLConnector**(string connectionString) |  |

**StiGraphQLConnector**(**connectionString**: string)

**Parameters**

- **connectionString** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Get** `static` | [StiGraphQLConnector](StiGraphQLConnector.md) |  |
| **GetColumns** | List<[StiDataColumnSchema](StiDataColumnSchema.md)> |  |
| **GetDataSet** | DataSet |  |
| **GetDataTable** *(+1 overloads)* | DataTable |  |
| **GetSampleConnectionString** | string | Returns sample of the connection string to this connector. |
| **LoadColumnsAndStringRowsFromPackedString** `static` | List<string[]> |  |
| **LoadColumnsAndStringRowsFromString** `static` | List<string[]> |  |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) |  |
| **TestConnection** | [StiTestConnectionResult](StiTestConnectionResult.md) |  |

---

### Method Details

#### Get `static`

**Get**(**connectionString**: string): [StiGraphQLConnector](StiGraphQLConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiGraphQLConnector](StiGraphQLConnector.md)


---

#### GetColumns

**GetColumns**(**collectionName**: string): List<[StiDataColumnSchema](StiDataColumnSchema.md)>

**Parameters**

- **collectionName** (string)  

**Returns** List<[StiDataColumnSchema](StiDataColumnSchema.md)>


---

#### GetDataSet

**GetDataSet**(**count**: int): DataSet

**Parameters**

- **count** (int)  

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

**GetDataTable**(**collectionName**: string, **query**: string, **variables**: Dictionary<string, object>, **index**: int?, **count**: int?): DataTable

**Parameters**

- **collectionName** (string)  
- **query** (string)  
- **variables** (Dictionary<string, object>)  
- **index** (int?)  
- **count** (int?)  

**Returns** DataTable


---

#### GetSampleConnectionString

**GetSampleConnectionString**(): string

Returns sample of the connection string to this connector.

**Returns** string


---

#### LoadColumnsAndStringRowsFromPackedString `static`

**LoadColumnsAndStringRowsFromPackedString**(**content**: string, ****: stringcolumns): List<string[]>

**Parameters**

- **content** (string)  
- **** (stringcolumns)  

**Returns** List<string[]>


---

#### LoadColumnsAndStringRowsFromString `static`

**LoadColumnsAndStringRowsFromString**(**content**: string, ****: stringcolumns): List<string[]>

**Parameters**

- **content** (string)  
- **** (stringcolumns)  

**Returns** List<string[]>


---

#### RetrieveSchema

**RetrieveSchema**(**allowException**: bool): [StiDataSchema](StiDataSchema.md)

**Parameters**

- **allowException** (bool)  

**Returns** [StiDataSchema](StiDataSchema.md)


---

#### TestConnection

**TestConnection**(): [StiTestConnectionResult](StiTestConnectionResult.md)

**Returns** [StiTestConnectionResult](StiTestConnectionResult.md)

