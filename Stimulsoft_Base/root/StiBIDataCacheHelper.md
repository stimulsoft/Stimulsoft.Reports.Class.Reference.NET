---
title: "StiBIDataCacheHelper Class"
---

## StiBIDataCacheHelper Class

**Namespace:** `Stimulsoft.Base`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clean** `static` | void |  |
| **CleanAll** `static` | void |  |
| **Exists** `static` | bool |  |
| **Get** `static` | DataTable |  |
| **GetRowCount** `static` | long |  |
| **GetTableCount** `static` | long |  |
| **GetTableName** `static` | string |  |
| **Remove** `static` | void |  |
| **RunQuery** `static` | DataTable |  |
| **SaveData** `static` | void |  |

---

### Method Details

#### Clean `static`

**Clean**(**appKey**: string): void

**Parameters**

- **appKey** (string)  


---

#### CleanAll `static`

**CleanAll**(): void


---

#### Exists `static`

**Exists**(**dataSource**: [IStiAppDataSource](IStiAppDataSource.md)): bool

**Parameters**

- **dataSource** ([IStiAppDataSource](IStiAppDataSource.md))  

**Returns** bool


---

#### Get `static`

**Get**(**dataSource**: [IStiAppDataSource](IStiAppDataSource.md), **loadData**: bool): DataTable

**Parameters**

- **dataSource** ([IStiAppDataSource](IStiAppDataSource.md))  
- **loadData** (bool)  

**Returns** DataTable


---

#### GetRowCount `static`

**GetRowCount**(**dataSource**: [IStiAppDataSource](IStiAppDataSource.md)): long

**Parameters**

- **dataSource** ([IStiAppDataSource](IStiAppDataSource.md))  

**Returns** long


---

#### GetTableCount `static`

**GetTableCount**(): long

**Returns** long


---

#### GetTableName `static`

**GetTableName**(**dataSource**: [IStiAppDataSource](IStiAppDataSource.md)): string

**Parameters**

- **dataSource** ([IStiAppDataSource](IStiAppDataSource.md))  

**Returns** string


---

#### Remove `static`

**Remove**(**dataSource**: [IStiAppDataSource](IStiAppDataSource.md)): void

**Parameters**

- **dataSource** ([IStiAppDataSource](IStiAppDataSource.md))  


---

#### RunQuery `static`

**RunQuery**(**query**: string): DataTable

**Parameters**

- **query** (string)  

**Returns** DataTable


---

#### SaveData `static`

**SaveData**(**dataSource**: [IStiAppDataSource](IStiAppDataSource.md), **dataTable**: DataTable): void

**Parameters**

- **dataSource** ([IStiAppDataSource](IStiAppDataSource.md))  
- **dataTable** (DataTable)  

