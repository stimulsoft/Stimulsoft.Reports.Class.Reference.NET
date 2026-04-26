---
title: "StiCosmosSqlApiHelper Class"
---

## StiCosmosSqlApiHelper Class

**Namespace:** `Stimulsoft.Base.Data.Connectors.Azure.Helper`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCosmosSqlApiHelper**(string connectionString, string nugetVersion) |  |

**StiCosmosSqlApiHelper**(**connectionString**: string, **nugetVersion**: string)

**Parameters**

- **connectionString** (string)  
- **nugetVersion** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetAssemblyData** | [StiDataAssemblyHelper](../../../../root/StiDataAssemblyHelper.md) |  |
| **GetColumns** | List<[StiDataColumnSchema](../../../../root/StiDataColumnSchema.md)> |  |
| **GetCosmosDbProvider** | object |  |
| **GetDataTable** | DataTable |  |
| **GetSampleConnectionString** `static` | string |  |
| **RetrieveSchema** | [StiDataSchema](../../../../root/StiDataSchema.md) |  |
| **TestConnection** | [StiTestConnectionResult](../../../../root/StiTestConnectionResult.md) |  |

---

### Method Details

#### GetAssemblyData

**GetAssemblyData**(): [StiDataAssemblyHelper](../../../../root/StiDataAssemblyHelper.md)

**Returns** [StiDataAssemblyHelper](../../../../root/StiDataAssemblyHelper.md)


---

#### GetColumns

**GetColumns**(**collectionName**: string): List<[StiDataColumnSchema](../../../../root/StiDataColumnSchema.md)>

**Parameters**

- **collectionName** (string)  

**Returns** List<[StiDataColumnSchema](../../../../root/StiDataColumnSchema.md)>


---

#### GetCosmosDbProvider

**GetCosmosDbProvider**(): object

**Returns** object


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

#### GetSampleConnectionString `static`

**GetSampleConnectionString**(): string

**Returns** string


---

#### RetrieveSchema

**RetrieveSchema**(**allowException**: bool): [StiDataSchema](../../../../root/StiDataSchema.md)

**Parameters**

- **allowException** (bool)  

**Returns** [StiDataSchema](../../../../root/StiDataSchema.md)


---

#### TestConnection

**TestConnection**(): [StiTestConnectionResult](../../../../root/StiTestConnectionResult.md)

**Returns** [StiTestConnectionResult](../../../../root/StiTestConnectionResult.md)

