---
title: "StiDataAdapterService Class"
---

## StiDataAdapterService Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiService](../../Stimulsoft_Base/Services/StiService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConnectDataSourceToData** | void |  |
| **Create** *(+1 overloads)* | StiDataSource | Creates a new Data Source and adds it to the dictionary. |
| **Edit** | bool | Calls the form for data source edition. |
| **GetColumnsFromData** *(+1 overloads)* | StiDataColumnsCollection | Returns a collection of columns of data. |
| **GetDataAdapter** `static` *(+1 overloads)* | [StiDataAdapterService](StiDataAdapterService.md) | Returns adapter for Data Source. |
| **GetDataCategoryName** | string | Returns name of category for data. |
| **GetDataSourceType** | Type | Returns the type of the data source. |
| **GetDataTypes** | Type[] | Returns the array of data types to which the Data Source may refer. |
| **GetMetadataProvider** | object |  |
| **GetParametersFromData** | StiDataParametersCollection | Returns a collection of parameters of data. |
| **GetSyntaxProvider** | object |  |
| **IsAdapterDataType** | bool | Returns true if the specified type is supported by this data adapters. |
| **New** | bool | Calls the form for a new data source edition. |
| **SetDataSourceNames** | void | Fills a name and alias of the data source relying on data. |
| **ToString** | string |  |

---

### Method Details

#### ConnectDataSourceToData

**ConnectDataSourceToData**(**dictionary**: StiDictionary, **dataSource**: StiDataSource, **loadData**: bool): void

**Parameters**

- **dictionary** (StiDictionary)  
- **dataSource** (StiDataSource)  
- **loadData** (bool)  


---

#### Create

**Create**(**dictionary**: StiDictionary, **addToDictionary**: bool): StiDataSource

Creates a new Data Source and adds it to the dictionary.

**Parameters**

- **dictionary** (StiDictionary) — Dictionary to add Data Source.  
- **addToDictionary** (bool)  

**Returns** StiDataSource — Created Data Source.

---

**Create**(**dictionary**: StiDictionary): StiDataSource

**Parameters**

- **dictionary** (StiDictionary)  

**Returns** StiDataSource


---

#### Edit

**Edit**(**dictionary**: StiDictionary, **dataSource**: StiDataSource): bool

Calls the form for data source edition.

**Parameters**

- **dictionary** (StiDictionary) — Dictionary in which data source is located.  
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

#### GetDataAdapter `static`

**GetDataAdapter**(**dataSource**: StiDataSource): [StiDataAdapterService](StiDataAdapterService.md)

Returns adapter for Data Source.

**Parameters**

- **dataSource** (StiDataSource) — Data Source for which retrieval of adapter will be done.  

**Returns** [StiDataAdapterService](StiDataAdapterService.md) — Adapter of data.

---

**GetDataAdapter**(**data**: [StiData](StiData.md)): [StiDataAdapterService](StiDataAdapterService.md)

Returns adapter for Data in DataStore.

**Parameters**

- **data** ([StiData](StiData.md)) — Data for which retrieval of adapter will be done.  

**Returns** [StiDataAdapterService](StiDataAdapterService.md) — Adapter of data.


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

Returns the type of the data source.

**Returns** Type — The type of Data Source.


---

#### GetDataTypes

**GetDataTypes**(): Type[]

Returns the array of data types to which the Data Source may refer.

**Returns** Type[] — Array of data types.


---

#### GetMetadataProvider

**GetMetadataProvider**(**connection**: IDbConnection): object

**Parameters**

- **connection** (IDbConnection)  

**Returns** object


---

#### GetParametersFromData

**GetParametersFromData**(**data**: [StiData](StiData.md), **dataSource**: StiDataSource): StiDataParametersCollection

Returns a collection of parameters of data.

**Parameters**

- **data** ([StiData](StiData.md)) — Data to find parameters.  
- **dataSource** (StiDataSource)  

**Returns** StiDataParametersCollection — Collection of parameters found.


---

#### GetSyntaxProvider

**GetSyntaxProvider**(): object

**Returns** object


---

#### IsAdapterDataType

**IsAdapterDataType**(**type**: Type): bool

Returns true if the specified type is supported by this data adapters.

**Parameters**

- **type** (Type)  

**Returns** bool


---

#### New

**New**(**dictionary**: StiDictionary, **dataSource**: StiDataSource): bool

Calls the form for a new data source edition.

**Parameters**

- **dictionary** (StiDictionary) — Dictionary in which Data Source is located.  
- **dataSource** (StiDataSource) — Data Source.  

**Returns** bool — Result of gialog form.


---

#### SetDataSourceNames

**SetDataSourceNames**(**data**: [StiData](StiData.md), **dataSource**: StiDataSource): void

Fills a name and alias of the data source relying on data.

**Parameters**

- **data** ([StiData](StiData.md)) — Data relying on which names will be filled.  
- **dataSource** (StiDataSource) — Data source in which names will be filled.  


---

#### ToString

**ToString**(): string

**Returns** string

