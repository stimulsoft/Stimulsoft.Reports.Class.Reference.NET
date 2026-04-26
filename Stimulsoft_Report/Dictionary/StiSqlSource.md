---
title: "StiSqlSource Class"
---

## StiSqlSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiDataTableSource](StiDataTableSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSqlSource**() | Creates a new object of the type StiSqlSource. |
| **StiSqlSource**(string nameInSource, string name) | Creates a new object of the type StiSqlSource. |
| **StiSqlSource**(string nameInSource, string name, string alias) | Creates a new object of the type StiSqlSource. |
| **StiSqlSource**(string nameInSource, string name, string alias, string sqlCommand) | Creates a new object of the type StiSqlSource. |
| **StiSqlSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart, bool reconnectOnEachRow, int commandTimeout, string key) |  |

**StiSqlSource**()

Creates a new object of the type StiSqlSource.

---

**StiSqlSource**(**nameInSource**: string, **name**: string)

Creates a new object of the type StiSqlSource.

**Parameters**

- **nameInSource** (string) — Name of Sql Connection in the DataStore.  
- **name** (string) — Data Source name.  

---

**StiSqlSource**(**nameInSource**: string, **name**: string, **alias**: string)

Creates a new object of the type StiSqlSource.

**Parameters**

- **nameInSource** (string) — Name of Sql Connection in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  

---

**StiSqlSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string)

Creates a new object of the type StiSqlSource.

**Parameters**

- **nameInSource** (string) — Name of SqlConnection in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  
- **sqlCommand** (string) — SQL statement to execute at the Data Source.  

---

**StiSqlSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string, **connectOnStart**: bool, **reconnectOnEachRow**: bool, **commandTimeout**: int, **key**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  
- **sqlCommand** (string)  
- **connectOnStart** (bool)  
- **reconnectOnEachRow** (bool)  
- **commandTimeout** (int)  
- **key** (string)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowExpressions** | bool |  |
| **CommandTimeout** | int |  |
| **DataAdapter** | IDbDataAdapter |  |
| **SqlCommand** | string |  |
| **Type** | [StiSqlSourceType](StiSqlSourceType.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddParameter** | StiDataParameter |  |
| **ConvertDbTypeToType** | Type | Internal use only. |
| **ConvertDbTypeToTypeInternal** | Type |  |
| **CreateConnector** | [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md) | Returns new data connector for this datasource. |
| **Disconnect** | void |  |
| **GetDataAdapterType** | Type |  |
| **GetFinalSqlCommand** | string |  |
| **GetParameterTypesEnum** | Type |  |
| **GetSqlFilterQuery** | string |  |
| **LoadFromJsonObject** | void |  |
| **RetrieveData** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **UpdateParameters** | void |  |

---

### Method Details

#### AddParameter

**AddParameter**(): StiDataParameter

**Returns** StiDataParameter


---

#### ConvertDbTypeToType

**ConvertDbTypeToType**(**sqlType**: int): Type

Internal use only.

**Parameters**

- **sqlType** (int)  

**Returns** Type


---

#### ConvertDbTypeToTypeInternal

**ConvertDbTypeToTypeInternal**(**sqlType**: int): Type

**Parameters**

- **sqlType** (int)  

**Returns** Type


---

#### CreateConnector

**CreateConnector**(**connectionString**: string): [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md)

Returns new data connector for this datasource.

**Parameters**

- **connectionString** (string)  

**Returns** [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md) — Created connector.


---

#### Disconnect

**Disconnect**(): void


---

#### GetDataAdapterType

**GetDataAdapterType**(): Type

**Returns** Type


---

#### GetFinalSqlCommand

**GetFinalSqlCommand**(): string

**Returns** string


---

#### GetParameterTypesEnum

**GetParameterTypesEnum**(): Type

**Returns** Type


---

#### GetSqlFilterQuery

**GetSqlFilterQuery**(): string

**Returns** string


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### RetrieveData

**RetrieveData**(**schemaOnly**: bool): void

**Parameters**

- **schemaOnly** (bool)  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)


---

#### UpdateParameters

**UpdateParameters**(): void

