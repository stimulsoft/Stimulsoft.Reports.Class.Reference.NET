---
title: "StiDataTransformationAdapterService Class"
---

## StiDataTransformationAdapterService Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Describes the adapter of the data transformation.

### Inheritance

Inherits from: [StiDataStoreAdapterService](StiDataStoreAdapterService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConnectDataSourceToData** | void |  |
| **Edit** | bool | Calls the form for Data Source edition. |
| **GetColumnsFromData** *(+1 overloads)* | StiDataColumnsCollection | Returns a collection of columns of data. |
| **GetDataCategoryName** | string | Returns name of category for data. |
| **GetDataSourceType** | Type | Returns the type of the Data Source. |
| **GetDataTypes** | Type[] | Returns the array of data types to which the Data Source may refer. |
| **GetParametersFromData** | StiDataParametersCollection | Returns a collection of parameters of data. |
| **New** | bool | Calls the form for a new Data Source edition. |

---

### Method Details

#### ConnectDataSourceToData

**ConnectDataSourceToData**(**dictionary**: StiDictionary, **dataSource**: StiDataSource, **loadData**: bool): void

**Parameters**

- **dictionary** (StiDictionary)  
- **dataSource** (StiDataSource)  
- **loadData** (bool)  


---

#### Edit

**Edit**(**dictionary**: StiDictionary, **dataSource**: StiDataSource): bool

Calls the form for Data Source edition.

**Parameters**

- **dictionary** (StiDictionary) — Dictionary in which Data Source is located.  
- **dataSource** (StiDataSource) — Data Source.  

**Returns** bool — Result of gialog form.


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

#### New

**New**(**dictionary**: StiDictionary, **dataSource**: StiDataSource): bool

Calls the form for a new Data Source edition.

**Parameters**

- **dictionary** (StiDictionary) — Dictionary in which Data Source is located.  
- **dataSource** (StiDataSource) — Data Source.  

**Returns** bool — Result of gialog form.

