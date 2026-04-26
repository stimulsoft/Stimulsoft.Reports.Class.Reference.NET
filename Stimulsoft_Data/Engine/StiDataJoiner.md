---
title: "StiDataJoiner Class"
---

## StiDataJoiner Class

**Namespace:** `Stimulsoft.Data.Engine`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **JoinEngine** `static` | StiDataJoinEngine |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **FindLink** `static` *(+1 overloads)* | [StiDataLink](StiDataLink.md) |  |
| **FindPath** `static` | List<[StiDataLink](StiDataLink.md)> |  |
| **Join** `static` | DataTable |  |

---

### Method Details

#### FindLink `static`

**FindLink**(**table1**: DataTable, **table2**: DataTable, **links**: List<[StiDataLink](StiDataLink.md)>): [StiDataLink](StiDataLink.md)

**Parameters**

- **table1** (DataTable)  
- **table2** (DataTable)  
- **links** (List<[StiDataLink](StiDataLink.md)>)  

**Returns** [StiDataLink](StiDataLink.md)

---

**FindLink**(**table1**: string, **table2**: string, **links**: List<[StiDataLink](StiDataLink.md)>): [StiDataLink](StiDataLink.md)

**Parameters**

- **table1** (string)  
- **table2** (string)  
- **links** (List<[StiDataLink](StiDataLink.md)>)  

**Returns** [StiDataLink](StiDataLink.md)


---

#### FindPath `static`

**FindPath**(**tables**: IEnumerable<string>, **links**: List<[StiDataLink](StiDataLink.md)>): List<[StiDataLink](StiDataLink.md)>

**Parameters**

- **tables** (IEnumerable<string>)  
- **links** (List<[StiDataLink](StiDataLink.md)>)  

**Returns** List<[StiDataLink](StiDataLink.md)>


---

#### Join `static`

**Join**(**tables**: IEnumerable<DataTable>, **links**: List<[StiDataLink](StiDataLink.md)>, **meters**: IEnumerable<[IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)>, **app**: [IStiApp](../../Stimulsoft_Base/root/IStiApp.md)): DataTable

**Parameters**

- **tables** (IEnumerable<DataTable>)  
- **links** (List<[StiDataLink](StiDataLink.md)>)  
- **meters** (IEnumerable<[IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)>)  
- **app** ([IStiApp](../../Stimulsoft_Base/root/IStiApp.md))  

**Returns** DataTable

