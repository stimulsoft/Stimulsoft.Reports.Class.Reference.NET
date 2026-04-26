---
title: "StiDataSourceHelper Class"
---

## StiDataSourceHelper Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDataSourcesFromDatabase** `static` | List<StiDataSource> |  |
| **GetDataSourcesUsedInRequestFromUsersVariables** `static` | Hashtable |  |
| **GetDatabaseFromDataSource** `static` | StiDatabase |  |
| **GetUsedDataSourcesNames** `static` | Hashtable |  |
| **GetUsedDataSourcesNamesList** `static` | List<string> |  |

---

### Method Details

#### GetDataSourcesFromDatabase `static`

**GetDataSourcesFromDatabase**(**report**: [StiReport](../root/StiReport.md), **database**: StiDatabase): List<StiDataSource>

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **database** (StiDatabase)  

**Returns** List<StiDataSource>


---

#### GetDataSourcesUsedInRequestFromUsersVariables `static`

**GetDataSourcesUsedInRequestFromUsersVariables**(**report**: [StiReport](../root/StiReport.md)): Hashtable

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  

**Returns** Hashtable


---

#### GetDatabaseFromDataSource `static`

**GetDatabaseFromDataSource**(**dataSource**: StiDataSource): StiDatabase

**Parameters**

- **dataSource** (StiDataSource)  

**Returns** StiDatabase


---

#### GetUsedDataSourcesNames `static`

**GetUsedDataSourcesNames**(**baseReport**: [StiReport](../root/StiReport.md), **businessObjectsNames**: Hashtable): Hashtable

**Parameters**

- **baseReport** ([StiReport](../root/StiReport.md))  
- **businessObjectsNames** (Hashtable)  

**Returns** Hashtable


---

#### GetUsedDataSourcesNamesList `static`

**GetUsedDataSourcesNamesList**(**report**: [StiReport](../root/StiReport.md)): List<string>

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  

**Returns** List<string>

