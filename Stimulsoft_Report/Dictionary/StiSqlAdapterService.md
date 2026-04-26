---
title: "StiSqlAdapterService Class"
---

## StiSqlAdapterService Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Describes the adapter for access to SqlConnection.

### Inheritance

Inherits from: [StiDataStoreAdapterService](StiDataStoreAdapterService.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **UseFailedConnectionsCache** `static` | bool | Gets or sets a value indicating whether to use failed connections cache to prevent performance degradation. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CloseConnection** | void |  |
| **ConnectDataSourceToData** | void |  |
| **CreateConnectionInDataStore** | void |  |
| **CreateConnector** *(+1 overloads)* | [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md) | Returns new data connector for this type of the database. |
| **GetColumnsFromData** *(+1 overloads)* | StiDataColumnsCollection | Returns a collection of columns of data. |
| **GetDataCategoryName** | string | Returns name of category for data. |
| **GetDataSourceType** | Type | Returns the type of the Data Source. |
| **GetDataTypes** | Type[] | Returns the array of data types to which the Data Source may refer. |
| **GetParametersFromData** | StiDataParametersCollection | Returns a collection of parameters of data. |
| **IsAdapterDataType** | bool | Returns true if the specified type is supported by this data adapters. |
| **OpenConnection** *(+1 overloads)* | void |  |
| **SetDataSourceNames** | void | Fills a name and alias of the Data Source relying on data. |
| **TestConnection** | string |  |

---

### Method Details

#### CloseConnection

**CloseConnection**(**data**: [StiData](StiData.md), **connection**: IDbConnection): void

**Parameters**

- **data** ([StiData](StiData.md))  
- **connection** (IDbConnection)  


---

#### ConnectDataSourceToData

**ConnectDataSourceToData**(**dictionary**: StiDictionary, **dataSource**: StiDataSource, **loadData**: bool): void

**Parameters**

- **dictionary** (StiDictionary)  
- **dataSource** (StiDataSource)  
- **loadData** (bool)  


---

#### CreateConnectionInDataStore

**CreateConnectionInDataStore**(**dictionary**: StiDictionary, **database**: StiSqlDatabase): void

**Parameters**

- **dictionary** (StiDictionary)  
- **database** (StiSqlDatabase)  


---

#### CreateConnector

**CreateConnector**(**data**: [StiData](StiData.md)): [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md)

Returns new data connector for this type of the database.

**Parameters**

- **data** ([StiData](StiData.md))  

**Returns** [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md) — Created connector.

---

**CreateConnector**(**connectionString**: string): [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md)

Returns new data connector for this type of the database.

**Parameters**

- **connectionString** (string)  

**Returns** [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md) — Created connector.


---

#### GetColumnsFromData

**GetColumnsFromData**(**data**: [StiData](StiData.md), **dataSource**: StiDataSource): StiDataColumnsCollection

Returns a collection of columns of data.

**Parameters**

- **data** ([StiData](StiData.md)) — Data to find column.  
- **dataSource** (StiDataSource)  

**Returns** StiDataColumnsCollection — Collection of columns found.

---

**GetColumnsFromData**(**data**: [StiData](StiData.md), **dataSource**: StiDataSource, **retrieveMode**: CommandBehavior): StiDataColumnsCollection

Returns a collection of columns of data.

**Parameters**

- **data** ([StiData](StiData.md)) — Data to find column.  
- **dataSource** (StiDataSource)  
- **retrieveMode** (CommandBehavior)  

**Returns** StiDataColumnsCollection — Collection of columns found.


---

#### GetDataCategoryName

**GetDataCategoryName**(**data**: [StiData](StiData.md)): string

Returns name of category for data.

**Parameters**

- **data** ([StiData](StiData.md))  

**Returns** string


---

#### GetDataSourceType

**GetDataSourceType**(): Type

Returns the type of the Data Source.

**Returns** Type — The type of Data Source.


---

#### GetDataTypes

**GetDataTypes**(): Type[]

Returns the array of data types to which the Data Source may refer.

**Returns** Type[] — Array of data types.


---

#### GetParametersFromData

**GetParametersFromData**(**data**: [StiData](StiData.md), **dataSource**: StiDataSource): StiDataParametersCollection

Returns a collection of parameters of data.

**Parameters**

- **data** ([StiData](StiData.md)) — Data to find parameters.  
- **dataSource** (StiDataSource)  

**Returns** StiDataParametersCollection — Collection of parameters found.


---

#### IsAdapterDataType

**IsAdapterDataType**(**type**: Type): bool

Returns true if the specified type is supported by this data adapters.

**Parameters**

- **type** (Type)  

**Returns** bool


---

#### OpenConnection

**OpenConnection**(**connection**: IDbConnection): void

**Parameters**

- **connection** (IDbConnection)  

---

**OpenConnection**(**connection**: IDbConnection, **data**: [StiData](StiData.md), **dictionary**: StiDictionary): void

**Parameters**

- **connection** (IDbConnection)  
- **data** ([StiData](StiData.md))  
- **dictionary** (StiDictionary)  


---

#### SetDataSourceNames

**SetDataSourceNames**(**data**: [StiData](StiData.md), **dataSource**: StiDataSource): void

Fills a name and alias of the Data Source relying on data.

**Parameters**

- **data** ([StiData](StiData.md)) — Data relying on which names will be filled.  
- **dataSource** (StiDataSource) — Data Source in which names will be filled.  


---

#### TestConnection

**TestConnection**(**connectionString**: string): string

**Parameters**

- **connectionString** (string)  

**Returns** string

