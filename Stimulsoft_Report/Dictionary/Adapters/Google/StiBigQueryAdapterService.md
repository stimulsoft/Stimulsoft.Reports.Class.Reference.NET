---
title: "StiBigQueryAdapterService Class"
---

## StiBigQueryAdapterService Class

**Namespace:** `Stimulsoft.Report.Dictionary.Adapters.Google`

### Inheritance

Inherits from: [StiNoSqlAdapterService](../../StiNoSqlAdapterService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConnectDataSourceToData** | void |  |
| **CreateConnector** | [StiNoSqlDataConnector](../../../../Stimulsoft_Base/root/StiNoSqlDataConnector.md) | Returns new data connector for this type of the database. |
| **GetColumnsFromData** *(+1 overloads)* | StiDataColumnsCollection | Returns a collection of columns of data. |
| **GetDataSourceType** | Type | Returns the type of the Data Source. |
| **GetParametersFromData** | StiDataParametersCollection | Returns a collection of parameters of data. |

---

### Method Details

#### ConnectDataSourceToData

**ConnectDataSourceToData**(**dictionary**: StiDictionary, **dataSource**: StiDataSource, **loadData**: bool): void

**Parameters**

- **dictionary** (StiDictionary)  
- **dataSource** (StiDataSource)  
- **loadData** (bool)  


---

#### CreateConnector

**CreateConnector**(**connectionString**: string): [StiNoSqlDataConnector](../../../../Stimulsoft_Base/root/StiNoSqlDataConnector.md)

Returns new data connector for this type of the database.

**Parameters**

- **connectionString** (string)  

**Returns** [StiNoSqlDataConnector](../../../../Stimulsoft_Base/root/StiNoSqlDataConnector.md) — Created connector.


---

#### GetColumnsFromData

**GetColumnsFromData**(**data**: [StiData](../../StiData.md), **dataSource**: StiDataSource): StiDataColumnsCollection

Returns a collection of columns of data.

**Parameters**

- **data** ([StiData](../../StiData.md)) — Data to find column.  
- **dataSource** (StiDataSource)  

**Returns** StiDataColumnsCollection — Collection of columns found.

---

**GetColumnsFromData**(**data**: [StiData](../../StiData.md), **dataSource**: StiDataSource, **retrieveMode**: CommandBehavior): StiDataColumnsCollection

Returns a collection of columns of data.

**Parameters**

- **data** ([StiData](../../StiData.md)) — Data to find column.  
- **dataSource** (StiDataSource)  
- **retrieveMode** (CommandBehavior)  

**Returns** StiDataColumnsCollection — Collection of columns found.


---

#### GetDataSourceType

**GetDataSourceType**(): Type

Returns the type of the Data Source.

**Returns** Type — The type of Data Source.


---

#### GetParametersFromData

**GetParametersFromData**(**data**: [StiData](../../StiData.md), **dataSource**: StiDataSource): StiDataParametersCollection

Returns a collection of parameters of data.

**Parameters**

- **data** ([StiData](../../StiData.md)) — Data to find parameters.  
- **dataSource** (StiDataSource)  

**Returns** StiDataParametersCollection — Collection of parameters found.

