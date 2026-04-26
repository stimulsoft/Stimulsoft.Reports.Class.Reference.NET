---
title: "StiAzureBlobStorageConnector Class"
---

## StiAzureBlobStorageConnector Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: StiDbNoSqlDataConnector  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Get** `static` | [StiAzureBlobStorageConnector](StiAzureBlobStorageConnector.md) |  |
| **GetBlobContentTypeOrDefault** | string | Try to connect to Azure Blob Storage using current connection string, download blob contents and infer type of data stored. |
| **GetBlobNamesList** | List<string> | Retrieve all blob names starting with specified , or all names if no specified. |
| **GetColumns** | List<[StiDataColumnSchema](StiDataColumnSchema.md)> |  |
| **GetContainerNamesList** | List<string> | Retrieve all container names starting with specified , or all names if no specified. |
| **GetDataTable** | DataTable |  |
| **GetSampleConnectionString** | string |  |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) |  |
| **TestConnection** | [StiTestConnectionResult](StiTestConnectionResult.md) |  |

---

### Method Details

#### Get `static`

**Get**(**connectionString**: string): [StiAzureBlobStorageConnector](StiAzureBlobStorageConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiAzureBlobStorageConnector](StiAzureBlobStorageConnector.md)


---

#### GetBlobContentTypeOrDefault

**GetBlobContentTypeOrDefault**(): string

Try to connect to Azure Blob Storage using current connection string, download blob contents and infer type of data stored.

**Returns** string — "Excel", "JSON" or "XML" if succeeded, or if failed. "CSV" cannot be inferred.


---

#### GetBlobNamesList

**GetBlobNamesList**(**prefix**: string): List<string>

Retrieve all blob names starting with specified , or all names if no specified.

**Parameters**

- **prefix** (string) — Only names starting with this prefix will be returned.  

**Returns** List<string>


---

#### GetColumns

**GetColumns**(**collectionName**: string): List<[StiDataColumnSchema](StiDataColumnSchema.md)>

**Parameters**

- **collectionName** (string)  

**Returns** List<[StiDataColumnSchema](StiDataColumnSchema.md)>


---

#### GetContainerNamesList

**GetContainerNamesList**(**prefix**: string): List<string>

Retrieve all container names starting with specified , or all names if no specified.

**Parameters**

- **prefix** (string) — Only names starting with this prefix will be returned.  

**Returns** List<string>


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

**RetrieveSchema**(**allowException**: bool): [StiDataSchema](StiDataSchema.md)

**Parameters**

- **allowException** (bool)  

**Returns** [StiDataSchema](StiDataSchema.md)


---

#### TestConnection

**TestConnection**(): [StiTestConnectionResult](StiTestConnectionResult.md)

**Returns** [StiTestConnectionResult](StiTestConnectionResult.md)

