---
title: "StiMsAnalysisServicesConnector Class"
---

## StiMsAnalysisServicesConnector Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: StiDbNoSqlDataConnector  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMsAnalysisServicesConnector**(string connectionString) |  |

**StiMsAnalysisServicesConnector**(**connectionString**: string)

**Parameters**

- **connectionString** (string)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **NuGetPackages** | string[] |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetColumns** | List<[StiDataColumnSchema](StiDataColumnSchema.md)> | Analysis services data structures may not be tables. Cannot get columns by table name, so query is used instead. |
| **GetDataTable** | DataTable |  |
| **GetSampleConnectionString** | string |  |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) |  |
| **TestConnection** | [StiTestConnectionResult](StiTestConnectionResult.md) |  |

---

### Method Details

#### GetColumns

**GetColumns**(**query**: string): List<[StiDataColumnSchema](StiDataColumnSchema.md)>

Analysis services data structures may not be tables. Cannot get columns by table name, so query is used instead.

**Parameters**

- **query** (string)  

**Returns** List<[StiDataColumnSchema](StiDataColumnSchema.md)>


---

#### GetDataTable

**GetDataTable**(**_**: string, **query**: string, **index**: int?, **count**: int?): DataTable

**Parameters**

- **_** (string)  
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

