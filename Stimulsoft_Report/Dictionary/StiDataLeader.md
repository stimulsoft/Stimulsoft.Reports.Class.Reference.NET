---
title: "StiDataLeader Class"
---

## StiDataLeader Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Connect** `static` *(+1 overloads)* | void |  |
| **Disconnect** `static` | void |  |
| **ExistsInCache** `static` | bool |  |
| **GetDataSet** `static` | DataSet |  |
| **RegData** `static` | void |  |
| **RetrieveData** `static` | void |  |
| **RetrieveSchema** `static` *(+1 overloads)* | [StiDataSchema](../../Stimulsoft_Base/root/StiDataSchema.md) |  |

---

### Method Details

#### Connect `static`

**Connect**(**dataSource**: StiDataSource, **loadData**: bool, **invokeEvents**: bool): void

**Parameters**

- **dataSource** (StiDataSource)  
- **loadData** (bool)  
- **invokeEvents** (bool)  

---

**Connect**(**dataSource**: StiDataSource, **datas**: [StiDataCollection](StiDataCollection.md), **loadData**: bool): void

**Parameters**

- **dataSource** (StiDataSource)  
- **datas** ([StiDataCollection](StiDataCollection.md))  
- **loadData** (bool)  


---

#### Disconnect `static`

**Disconnect**(**dataSource**: StiDataSource): void

**Parameters**

- **dataSource** (StiDataSource)  


---

#### ExistsInCache `static`

**ExistsInCache**(**database**: StiDatabase, **dictionary**: StiDictionary): bool

**Parameters**

- **database** (StiDatabase)  
- **dictionary** (StiDictionary)  

**Returns** bool


---

#### GetDataSet `static`

**GetDataSet**(**connector**: [StiFileDataConnector](../../Stimulsoft_Base/root/StiFileDataConnector.md), **options**: [StiFileDataOptions](../../Stimulsoft_Base/root/StiFileDataOptions.md)): DataSet

**Parameters**

- **connector** ([StiFileDataConnector](../../Stimulsoft_Base/root/StiFileDataConnector.md))  
- **options** ([StiFileDataOptions](../../Stimulsoft_Base/root/StiFileDataOptions.md))  

**Returns** DataSet


---

#### RegData `static`

**RegData**(**database**: StiDatabase, **dictionary**: StiDictionary, **loadData**: bool): void

**Parameters**

- **database** (StiDatabase)  
- **dictionary** (StiDictionary)  
- **loadData** (bool)  


---

#### RetrieveData `static`

**RetrieveData**(**dataSource**: [StiSqlSource](StiSqlSource.md), **schemaOnly**: bool): void

**Parameters**

- **dataSource** ([StiSqlSource](StiSqlSource.md))  
- **schemaOnly** (bool)  


---

#### RetrieveSchema `static`

**RetrieveSchema**(**connector**: [StiFileDataConnector](../../Stimulsoft_Base/root/StiFileDataConnector.md), **options**: [StiFileDataOptions](../../Stimulsoft_Base/root/StiFileDataOptions.md)): [StiDataSchema](../../Stimulsoft_Base/root/StiDataSchema.md)

**Parameters**

- **connector** ([StiFileDataConnector](../../Stimulsoft_Base/root/StiFileDataConnector.md))  
- **options** ([StiFileDataOptions](../../Stimulsoft_Base/root/StiFileDataOptions.md))  

**Returns** [StiDataSchema](../../Stimulsoft_Base/root/StiDataSchema.md)

---

**RetrieveSchema**(**connector**: [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md), **allowException**: bool): [StiDataSchema](../../Stimulsoft_Base/root/StiDataSchema.md)

**Parameters**

- **connector** ([StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md))  
- **allowException** (bool)  

**Returns** [StiDataSchema](../../Stimulsoft_Base/root/StiDataSchema.md)

