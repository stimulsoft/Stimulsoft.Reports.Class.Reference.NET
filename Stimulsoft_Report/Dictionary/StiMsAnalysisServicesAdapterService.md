---
title: "StiMsAnalysisServicesAdapterService Class"
---

## StiMsAnalysisServicesAdapterService Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiNoSqlAdapterService](StiNoSqlAdapterService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConnectDataSourceToData** | void |  |
| **CreateConnector** | [StiNoSqlDataConnector](../../Stimulsoft_Base/root/StiNoSqlDataConnector.md) |  |
| **GetColumnsFromData** *(+1 overloads)* | StiDataColumnsCollection |  |
| **GetDataSourceType** | Type |  |
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

#### CreateConnector

**CreateConnector**(**connectionString**: string): [StiNoSqlDataConnector](../../Stimulsoft_Base/root/StiNoSqlDataConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiNoSqlDataConnector](../../Stimulsoft_Base/root/StiNoSqlDataConnector.md)


---

#### GetColumnsFromData

**GetColumnsFromData**(**data**: [StiData](StiData.md), **dataSource**: StiDataSource): StiDataColumnsCollection

**Parameters**

- **data** ([StiData](StiData.md))  
- **dataSource** (StiDataSource)  

**Returns** StiDataColumnsCollection

---

**GetColumnsFromData**(**data**: [StiData](StiData.md), **dataSource**: StiDataSource, **retrieveMode**: CommandBehavior): StiDataColumnsCollection

**Parameters**

- **data** ([StiData](StiData.md))  
- **dataSource** (StiDataSource)  
- **retrieveMode** (CommandBehavior)  

**Returns** StiDataColumnsCollection


---

#### GetDataSourceType

**GetDataSourceType**(): Type

**Returns** Type


---

#### GetParametersFromData

**GetParametersFromData**(**data**: [StiData](StiData.md), **dataSource**: StiDataSource): StiDataParametersCollection

**Parameters**

- **data** ([StiData](StiData.md))  
- **dataSource** (StiDataSource)  

**Returns** StiDataParametersCollection

