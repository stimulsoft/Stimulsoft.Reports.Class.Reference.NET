---
title: "StiSqlDataAnalyzer Class"
---

## StiSqlDataAnalyzer Class

**Namespace:** `Stimulsoft.Data.Engine`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BuildJoinQuery** `static` | string |  |
| **BuildSelectQuery** `static` | string |  |

---

### Method Details

#### BuildJoinQuery `static`

**BuildJoinQuery**(**path**: List<[StiDataLink](StiDataLink.md)>, **realDataNames**: List<string>, **dataNames**: List<string>): string

**Parameters**

- **path** (List<[StiDataLink](StiDataLink.md)>)  
- **realDataNames** (List<string>)  
- **dataNames** (List<string>)  

**Returns** string


---

#### BuildSelectQuery `static`

**BuildSelectQuery**(**dataSources**: IEnumerable<[IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md)>, **app**: [IStiApp](../../Stimulsoft_Base/root/IStiApp.md)): string

**Parameters**

- **dataSources** (IEnumerable<[IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md)>)  
- **app** ([IStiApp](../../Stimulsoft_Base/root/IStiApp.md))  

**Returns** string

