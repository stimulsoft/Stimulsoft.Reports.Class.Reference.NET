---
title: "StiDBaseAdapterService Class"
---

## StiDBaseAdapterService Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Describes the adapter for access to dBase files.

### Inheritance

Inherits from: [StiFileAdapterService](StiFileAdapterService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConnectDataSourceToData** | void |  |
| **CreateConnector** | [StiFileDataConnector](../../Stimulsoft_Base/root/StiFileDataConnector.md) | Returns new data connector for this type of the database. |
| **GetColumnsFromData** *(+1 overloads)* | StiDataColumnsCollection | Returns a collection of columns of data. |
| **GetDataSourceType** | Type | Returns the type of the Data Source. |
| **GetDataTypes** | Type[] | Returns the array of data types to which the Data Source may refer. |
| **GetParametersFromData** | StiDataParametersCollection | Returns a collection of parameters of data. |
| **SetDataSourceNames** | void | Fills a name and alias of the Data Source relying on data. |

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

**CreateConnector**(): [StiFileDataConnector](../../Stimulsoft_Base/root/StiFileDataConnector.md)

Returns new data connector for this type of the database.

**Returns** [StiFileDataConnector](../../Stimulsoft_Base/root/StiFileDataConnector.md) — Created connector.


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

#### SetDataSourceNames

**SetDataSourceNames**(**data**: [StiData](StiData.md), **dataSource**: StiDataSource): void

Fills a name and alias of the Data Source relying on data.

**Parameters**

- **data** ([StiData](StiData.md)) — Data relying on which names will be filled.  
- **dataSource** (StiDataSource) — Data Source in which names will be filled.  

