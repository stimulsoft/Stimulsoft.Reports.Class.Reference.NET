---
title: "StiGoogleAnalyticsConnector Class"
---

## StiGoogleAnalyticsConnector Class

**Namespace:** `Stimulsoft.Base.Data.Connectors.Google`

### Inheritance

Inherits from: StiDbNoSqlDataConnector  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGoogleAnalyticsConnector**(string connectionString) |  |

**StiGoogleAnalyticsConnector**(**connectionString**: string)

**Parameters**

- **connectionString** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Get** `static` | [StiGoogleAnalyticsConnector](StiGoogleAnalyticsConnector.md) |  |
| **GetColumns** | List<[StiDataColumnSchema](../../../root/StiDataColumnSchema.md)> |  |
| **GetDataTable** | DataTable |  |
| **GetSampleConnectionString** | string |  |
| **RetrieveSchema** | [StiDataSchema](../../../root/StiDataSchema.md) |  |
| **TestConnection** | [StiTestConnectionResult](../../../root/StiTestConnectionResult.md) |  |

---

### Method Details

#### Get `static`

**Get**(**connectionString**: string): [StiGoogleAnalyticsConnector](StiGoogleAnalyticsConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiGoogleAnalyticsConnector](StiGoogleAnalyticsConnector.md)


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

