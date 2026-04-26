---
title: "StiCDataConnectCloudAdapterService Class"
---

## StiCDataConnectCloudAdapterService Class

**Namespace:** `Stimulsoft.Report.Dictionary.Adapters.OnlineService`

### Inheritance

Inherits from: [StiSqlAdapterService](../../StiSqlAdapterService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiSqlDataConnector](../../../../Stimulsoft_Base/root/StiSqlDataConnector.md) |  |
| **GetColumnsFromData** | StiDataColumnsCollection |  |
| **GetDataSourceType** | Type |  |

---

### Method Details

#### CreateConnector

**CreateConnector**(**connectionString**: string): [StiSqlDataConnector](../../../../Stimulsoft_Base/root/StiSqlDataConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiSqlDataConnector](../../../../Stimulsoft_Base/root/StiSqlDataConnector.md)


---

#### GetColumnsFromData

**GetColumnsFromData**(**data**: [StiData](../../StiData.md), **dataSource**: StiDataSource, **retrieveMode**: CommandBehavior): StiDataColumnsCollection

**Parameters**

- **data** ([StiData](../../StiData.md))  
- **dataSource** (StiDataSource)  
- **retrieveMode** (CommandBehavior)  

**Returns** StiDataColumnsCollection


---

#### GetDataSourceType

**GetDataSourceType**(): Type

**Returns** Type

