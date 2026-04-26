---
title: "StiDataPicker Class"
---

## StiDataPicker Class

**Namespace:** `Stimulsoft.Data.Engine`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CleanCache** `static` | void |  |
| **ExistsInCache** `static` | bool |  |
| **Fetch** `static` *(+1 overloads)* | DataTable |  |
| **GetDataTable** `static` | DataTable |  |
| **GetFromCache** `static` | DataTable |  |
| **IsAllBICached** `static` | bool |  |
| **RetrieveUsedDataSources** `static` | IEnumerable<[IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md)> | Fetches all used data sources in the specified query. |

---

### Method Details

#### CleanCache `static`

**CleanCache**(**appKey**: string): void

**Parameters**

- **appKey** (string)  


---

#### ExistsInCache `static`

**ExistsInCache**(**dataSource**: [IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md)): bool

**Parameters**

- **dataSource** ([IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md))  

**Returns** bool


---

#### Fetch `static`

**Fetch**(**app**: [IStiApp](../../Stimulsoft_Base/root/IStiApp.md), **dataSourceName**: string, **option**: [StiDataRequestOption](StiDataRequestOption.md)): DataTable

**Parameters**

- **app** ([IStiApp](../../Stimulsoft_Base/root/IStiApp.md))  
- **dataSourceName** (string)  
- **option** ([StiDataRequestOption](StiDataRequestOption.md))  

**Returns** DataTable

---

**Fetch**(**app**: [IStiApp](../../Stimulsoft_Base/root/IStiApp.md), **dataSource**: [IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md), **option**: [StiDataRequestOption](StiDataRequestOption.md)): DataTable

**Parameters**

- **app** ([IStiApp](../../Stimulsoft_Base/root/IStiApp.md))  
- **dataSource** ([IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md))  
- **option** ([StiDataRequestOption](StiDataRequestOption.md))  

**Returns** DataTable


---

#### GetDataTable `static`

**GetDataTable**(**app**: [IStiApp](../../Stimulsoft_Base/root/IStiApp.md), **dataSource**: [IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md), **option**: [StiDataRequestOption](StiDataRequestOption.md)): DataTable

**Parameters**

- **app** ([IStiApp](../../Stimulsoft_Base/root/IStiApp.md))  
- **dataSource** ([IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md))  
- **option** ([StiDataRequestOption](StiDataRequestOption.md))  

**Returns** DataTable


---

#### GetFromCache `static`

**GetFromCache**(**dataSource**: [IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md)): DataTable

**Parameters**

- **dataSource** ([IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md))  

**Returns** DataTable


---

#### IsAllBICached `static`

**IsAllBICached**(**query**: [IStiQueryObject](IStiQueryObject.md), **group**: string, **option**: [StiDataRequestOption](StiDataRequestOption.md)): bool

**Parameters**

- **query** ([IStiQueryObject](IStiQueryObject.md))  
- **group** (string)  
- **option** ([StiDataRequestOption](StiDataRequestOption.md))  

**Returns** bool


---

#### RetrieveUsedDataSources `static`

**RetrieveUsedDataSources**(**query**: [IStiQueryObject](IStiQueryObject.md), **group**: string, **filterNames**: IEnumerable<string>): IEnumerable<[IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md)>

Fetches all used data sources in the specified query.

**Parameters**

- **query** ([IStiQueryObject](IStiQueryObject.md))  
- **group** (string)  
- **filterNames** (IEnumerable<string>)  

**Returns** IEnumerable<[IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md)>

