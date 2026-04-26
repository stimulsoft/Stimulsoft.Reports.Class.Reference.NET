---
title: "StiGoogleSheetsAdapterService Class"
---

## StiGoogleSheetsAdapterService Class

**Namespace:** `Stimulsoft.Report.Dictionary.Adapters.Google`

### Inheritance

Inherits from: [StiDataStoreAdapterService](../../StiDataStoreAdapterService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConnectDataSourceToData** | void |  |
| **CreateConnectionInDataStore** | void |  |
| **CreateConnector** | [StiGoogleSheetsConnector](../../../../Stimulsoft_Base/Data/Connectors/Google/StiGoogleSheetsConnector.md) | Returns new data connector for this type of the database. |
| **GetColumnsFromData** *(+1 overloads)* | StiDataColumnsCollection | Returns a collection of columns of data. |
| **GetDataCategoryName** | string |  |
| **GetDataSourceType** | Type | Returns the type of the Data Source. |
| **GetDataTypes** | Type[] |  |
| **GetParametersFromData** | StiDataParametersCollection |  |

---

### Method Details

#### ConnectDataSourceToData

**ConnectDataSourceToData**(**dictionary**: StiDictionary, **dataSource**: StiDataSource, **loadData**: bool): void

**Parameters**

- **dictionary** (StiDictionary)  
- **dataSource** (StiDataSource)  
- **loadData** (bool)  


---

#### CreateConnectionInDataStore

**CreateConnectionInDataStore**(**dictionary**: StiDictionary, **database**: [StiGoogleSheetsDatabase](../../Databases/Google/StiGoogleSheetsDatabase.md)): void

**Parameters**

- **dictionary** (StiDictionary)  
- **database** ([StiGoogleSheetsDatabase](../../Databases/Google/StiGoogleSheetsDatabase.md))  


---

#### CreateConnector

**CreateConnector**(**clientId**: string, **clientSecret**: string, **spreadsheetId**: string, **firstRowIsHeader**: bool): [StiGoogleSheetsConnector](../../../../Stimulsoft_Base/Data/Connectors/Google/StiGoogleSheetsConnector.md)

Returns new data connector for this type of the database.

**Parameters**

- **clientId** (string)  
- **clientSecret** (string)  
- **spreadsheetId** (string)  
- **firstRowIsHeader** (bool)  

**Returns** [StiGoogleSheetsConnector](../../../../Stimulsoft_Base/Data/Connectors/Google/StiGoogleSheetsConnector.md) — Created connector.


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

#### GetDataCategoryName

**GetDataCategoryName**(**data**: [StiData](../../StiData.md)): string

**Parameters**

- **data** ([StiData](../../StiData.md))  

**Returns** string


---

#### GetDataSourceType

**GetDataSourceType**(): Type

Returns the type of the Data Source.

**Returns** Type — The type of Data Source.


---

#### GetDataTypes

**GetDataTypes**(): Type[]

**Returns** Type[]


---

#### GetParametersFromData

**GetParametersFromData**(**data**: [StiData](../../StiData.md), **dataSource**: StiDataSource): StiDataParametersCollection

**Parameters**

- **data** ([StiData](../../StiData.md))  
- **dataSource** (StiDataSource)  

**Returns** StiDataParametersCollection

