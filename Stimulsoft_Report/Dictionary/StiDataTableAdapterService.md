---
title: "StiDataTableAdapterService Class"
---

## StiDataTableAdapterService Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Describes the adapter for access to DataTable.

### Inheritance

Inherits from: [StiDataStoreAdapterService](StiDataStoreAdapterService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConnectDataSourceToData** | void |  |
| **GetColumnsFromData** *(+1 overloads)* | StiDataColumnsCollection | Returns a collection of columns of data. |
| **GetDataCategoryName** | string | Returns name of category for data. |
| **GetDataFromDataSource** | [StiData](StiData.md) |  |
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

#### GetDataFromDataSource

**GetDataFromDataSource**(**dictionary**: StiDictionary, **dataSource**: StiDataSource): [StiData](StiData.md)

**Parameters**

- **dictionary** (StiDictionary)  
- **dataSource** (StiDataSource)  

**Returns** [StiData](StiData.md)


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
- **dataSource** (StiDataSource) — Data source in which names will be filled.  

